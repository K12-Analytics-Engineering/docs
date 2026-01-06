# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Mintlify documentation site for K12 Analytics Engineering, a managed data platform for K12 organizations. The documentation covers the data warehouse, pricing, and additional functionality.

## Development Commands

```bash
# Install Mintlify CLI
npm i -g mintlify

# Start local development server (runs on localhost:3000)
mintlify dev

# Check for broken links
mintlify broken-links
```

## Repository Structure

- `docs.json` - Main configuration file for Mintlify (navigation, theme colors, links)
- `get-started/` - Introduction, pricing, FAQ, and support documentation
- `data-warehouse/` - Technical documentation on wide tables and metrics
- `addt-functionality/` - Connected Sheets, data drops functionality
- `advanced/` - Customization and row-level security docs
- `snippets/` - Reusable MDX content snippets
- `images/` - Documentation images and diagrams

## Writing Documentation

- All documentation pages are `.mdx` files (Markdown with JSX support)
- Page metadata (title, description) goes in YAML frontmatter at the top
- New pages must be added to the `navigation` array in `docs.json` to appear in the sidebar
- Use snippets in `snippets/` directory for content that appears in multiple places
