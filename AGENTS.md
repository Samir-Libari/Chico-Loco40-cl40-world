> # AGENTS.md — Development & Writing Guidelines
>
> This document defines the core guidelines, architecture rules, and writing standards for AI agents and developers contributing to the **CL40 World** Mintlify documentation repository.
>
> ---
>
> ## About This Project
>
> This documentation suite is built on top of **Mintlify** to serve the global **CL40 World Ecosystem** across Gaming, Software, IP/Music Rights, Support, and Media.
>
> - **Pages:** Written in MDX files (`.mdx`) with YAML frontmatter.
> - **Configuration:** Managed globally via `docs.json`.
> - **MCP Editing:** Use the Mintlify MCP server (`https://mcp.mintlify.com`) to manage content and site settings.
> - **MCP Knowledge:** Query Mintlify platform rules using `https://www.mintlify.com/docs/mcp`.
>
> ---
>
> ## First-Time Setup
>
> For Mintlify product knowledge, custom components, full configuration syntax, and platform standards, initialize the official skill:
>
> ```bash
> npx skills add [https://mintlify.com/docs](https://mintlify.com/docs)
> ```

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

{/* Add product-specific terms and preferred usage */}

{/* Example: Use "workspace" not "project", "member" not "user" */}

## Style Preferences

Follow these core writing rules for all current and future documentation pages:

- **Voice:** Use active voice and second person ("you").
- **Conciseness:** Keep sentences brief and direct — strictly one idea per sentence.
- **Headings:** Apply sentence case for all headings (`## Get started`, `## Security policy`).
- **UI Elements:** Use **Bold** formatting for buttons and interface actions (e.g., Click **Publish**).
- **Technical References:** Use `code formatting` for file paths, commands, code blocks, and system parameters (e.g., `docs.json`, `npm run dev`).

## Content Boundaries & Ecosystem Scope

All documentation must adhere strictly to the established **CL40 World** brand identities:

- **Space:** Gaming architecture, native C++ plugins, low-latency audio.
- **Codes:** Developer tools, CLI releases, SDK integrations, API limits.
- **Rights:** Audio master catalog, ISRC tracking, copyright compliance.
- **Humanity:** Community initiatives, support streams, developer outreach.

## Primary Contact

For technical queries or security disclosures:

- **Primary Support:** [founder.american@cl40.world](mailto:founder.american@cl40.world)
- **Security Desk:** [only@cl40.world](mailto:only@cl40.world)
