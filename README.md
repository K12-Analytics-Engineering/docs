# K12 Analytics Engineering Documentation

Documentation site for K12 Analytics Engineering, built with [Mintlify](https://mintlify.com/).

## Local Development

### Prerequisites
- Node.js installed

### Install Mintlify CLI
```bash
npm i -g mintlify
```

### Run Development Server
```bash
mintlify dev
```
This starts the local server at http://localhost:3000 with hot reload.

### Check for Broken Links
```bash
mintlify broken-links
```

## Making Updates
- Documentation pages are `.mdx` files (Markdown with JSX)
- Add page metadata (title, description) in YAML frontmatter
- New pages must be added to `docs.json` navigation to appear in sidebar
