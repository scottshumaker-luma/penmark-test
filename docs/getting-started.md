# Getting Started

Welcome to the documentation!

## Installation

Run the following command to install:

```bash
npm install penmark
```

## Configuration

Create a config file in your project root:

```json
{
  "docsPath": "docs/",
  "branch": "main"
}
```

## Usage

After installation, you can start the editor:

```bash
npx penmark serve
```

This will open the editor at `http://localhost:3000`.

## FAQ

**Q: Can I use this with private repos?**
A: Yes! Just authenticate with GitHub OAuth.

**Q: What markdown features are supported?**
A: We support GFM (GitHub Flavored Markdown) including tables, task lists, and code blocks.
