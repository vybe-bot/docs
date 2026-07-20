# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use **VybeBot** for the product and **Vyber** for the project builder interface.
- A **workspace** contains members, billing, shared knowledge, connections, skills, and projects.
- A **project** is one bot codebase. A project can contain multiple branches and chat sessions.
- A **branch** is an isolated line of code, AI history, connector links, deployment state, domain, and persistent storage.
- Use **member** for a person in a workspace and **collaborator** for project-specific access.
- Use **AI credits** for generation usage and **cloud credits** for deployed runtime usage. Never call them both "credits" when the distinction matters.
- Use **app connector** for a service that can be used by generated code at runtime.
- Use **chat connector** or **MCP server** for a tool the Vyber agent can use during generation.
- Use **VybeBot Cloud** for managed project hosting.

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Document customer-facing behavior that exists in the current VybeBot application.
- Document plan-dependent behavior without hard-coding prices or limits that are loaded from the live plan catalog.
- Do not document internal admin screens, service credentials, private infrastructure addresses, or secret values.
- Explain operator architecture only at a high level. Keep deployment-provider procedures in the application repository.
- Mark unfinished or disabled product behavior as unavailable instead of presenting it as a current feature.
- Never include real bot tokens, OAuth credentials, API keys, or customer data in examples.
