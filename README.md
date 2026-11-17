# Cardinal Query skill

Search Cardinal Data Lake logs as ranked log patterns or raw rows, discover log labels and their values, and investigate recurring Issues from GitHub Copilot. The skill connects directly to your hosted Query API using an organization API key.

Windows uses the built-in Windows PowerShell 5.1. The Windows workflow runs without Python or PowerShell 7. Linux and macOS use Python 3.9 or newer.

1. Download the [v0.4.0 skill ZIP](https://github.com/cardinalhq/cardinal-query-skill/releases/download/v0.4.0/cardinal-query.zip).
2. Extract it and copy the entire `cardinal-query` folder into `.github/skills/cardinal-query` in your repository. If you already installed an older version, replace that skill folder.
3. Follow the [setup guide](.github/skills/cardinal-query/references/setup.md) for credentials and instructions for Copilot CLI, IntelliJ, and GitHub.com agent sessions.

This repository distributes the reviewed skill from [Cardinal Agent Plugins](https://github.com/cardinalhq/cardinal-agent-plugins/tree/42d87abee9064166190a017659ded7a019d9513f/.github/skills/cardinal-query).
