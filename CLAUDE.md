# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Mintlify documentation site for "CurrentClient" - a documentation starter kit that uses MDX for content and JSON configuration for site structure.

## Development Commands

### Local Development
```bash
# Install Mintlify CLI globally (required for development)
npm i -g mint

# Start local development server
mint dev

# Start on custom port
mint dev --port 3333

# Update CLI to latest version
npm mint update
```

### Validation and Testing
```bash
# Check for broken links in documentation
mint broken-links
```

## Architecture

### Configuration Files
- `docs.json`: Main configuration file defining navigation, theming, and site structure
- All navigation, tabs, groups, and page organization is controlled through this file
- Defines color scheme, logos, footer, and contextual options

### Content Structure
- **MDX Files**: All content pages use MDX format with YAML frontmatter
- **Navigation Tabs**: 
  - "Guides" tab: Getting started, customization, writing content, AI tools
  - "API reference" tab: API documentation and endpoint examples
- **Key Directories**:
  - `/essentials/`: Core documentation features (markdown, code, images, settings, navigation)
  - `/ai-tools/`: AI tool integrations (cursor, claude-code, windsurf)
  - `/api-reference/`: API documentation and endpoint examples
  - `/snippets/`: Reusable content snippets
  - `/images/`: Static image assets
  - `/logo/`: Light and dark theme logos

### Content Standards
- All MDX files require YAML frontmatter with `title` and `description`
- Uses Mintlify components like `<Card>`, `<Columns>`, `<Steps>`, `<Info>`, `<Frame>`, `<AccordionGroup>`
- Supports contextual options including copy, view, chatgpt, claude, perplexity, mcp, cursor, vscode

### File Organization
- Root pages: `index.mdx` (introduction), `quickstart.mdx`, `development.mdx`
- Content organized by functional groups matching navigation structure
- OpenAPI specification available at `/api-reference/openapi.json`

## Development Notes

- Local preview runs on `http://localhost:3000` by default
- Changes automatically deploy to production when pushed to default branch
- Requires Node.js version 19 or higher
- Uses Mintlify's deployment system via GitHub app integration