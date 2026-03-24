# Architecture

## Overview

Penmark is a Next.js application that provides a WYSIWYG editor for markdown files stored in git.

## Components

### Editor

The editor is built on Tiptap, a headless rich text editor based on ProseMirror.

### Git Integration

All document operations go through the GitHub API:

- Reading files from branches
- Creating draft branches for editing
- Committing changes
- Merging (publishing) to main

### Database

Comments and document locks are stored in Neon Postgres.

## Data Flow

1. User opens a document → fetched from GitHub API
2. User clicks Edit → lock acquired, draft branch created
3. User edits → auto-saved as commits to draft branch
4. User publishes → draft branch merged to main
