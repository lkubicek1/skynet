# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Project Overview
Skynet is a curated collection of Model Context Protocol (MCP) servers and tools. Currently, it functions as a central reference and documentation repository for the MCP ecosystem.

## Architecture
The repository structure is minimal, focusing on documentation:
- `README.md`: Acts as the primary registry, listing featured MCP servers and tools categorized by their function (e.g., Development & Infrastructure, Data & Knowledge, AI & Reasoning Context).

## Common Tasks

### Adding a New MCP Server
To add a new tool or server to the registry:
1.  **Categorize**: Determine if the tool fits into "Development & Infrastructure", "Data & Knowledge", or "AI & Reasoning Context". Create a new category if necessary.
2.  **Format**: Use the existing list format:
    ```markdown
    - **[Name](URL)**
      Description of the tool and its capabilities.
    ```
3.  **Verify**: Ensure the provided link is accessible and the description is accurate.

### Maintenance
- **Link Checking**: Periodically verify that all external links in `README.md` are still valid.
- **Updates**: Keep descriptions up-to-date with the latest features of the referenced MCP tools.

## Rules & Conventions
- **Formatting**: Maintain consistent Markdown formatting for list items and headers.
- **Tone**: Keep descriptions concise and objective.
