# Model Context Protocol (MCP) Adoption Reference

> Internal reference: Model Context Protocol adoption notes
> Generated from live GitHub API, web research, and Amazon search results at the time of this report.

---

## 1. Web Research Section

A Google search for "Model Context Protocol" was run via the Google search scraper. The tool returned the following:

- **Page title:** Google search results for "Model Context Protocol"
- **URL:** `https://www.google.com/search?q=Model+Context+Protocol` (fetched via oxylabs Google search scraper)
- **AI-overview text returned:** The Google search returned structured results with page titles and URLs. Because the scraper hit a quota limit (HTTP 429: "Your current plan's quota has been reached"), no verbatim AI-overview text fragments were captured from the search itself.
- **Supporting live content gathered instead:** The MCP specification and official documentation are hosted at `https://modelcontextprotocol.io`. The official GitHub repo (see Ecosystem section) states: "This repo contains the: MCP specification, MCP protocol schema, and Official MCP documentation." The spec was created by David Soria Parra and Justin Spahr-Summers per the repo README.
- **Note:** Page titles/URLs cited from the live responses are taken from GitHub repository data and the MCP documentation page, since the Google search scraper returned no usable results.

---

## 2. Ecosystem Section

### 2.1 `modelcontextprotocol/modelcontextprotocol`
- **Full name (owner/repo):** modelcontextprotocol/modelcontextprotocol
- **Star count:** 9,750
- **Open issue count:** 124
- **Default branch:** main
- **Latest commit on default branch (author date):** 2026-11-22T00:31:13Z, full SHA `862397cec702e8f828713071da501cf56158e8fc` — "docs: add Archestra.AI and mcp-use to the extension client matrix (#3574)"
- **Note:** GitHub API reported `stargazers_count: 9750` and `open_issues_count: 124` at time of fetch.

### 2.2 `modelcontextprotocol/actions`
- **Full name (owner/repo):** modelcontextprotocol/actions
- **Star count:** 8
- **Open issue count:** 0
- **Default branch:** main
- **Latest commit on default branch:** pushed_at 2026-11-04T23:26:52Z
- **Note:** GitHub API reported `stargazers_count: 8` and `open_issues_count: 0` at time of fetch.

### 2.3 GitHub Actions workflows in `modelcontextprotocol/servers`
The directory `.github/workflows/` exists and contains the following 24 workflow files (filenames only):

- datadog-synthetics.yml
- dco.yml
- dependabot-alerts.yml
- dependency-refresh.yml
- everything-mcp-diff.yml
- image-smoke.yml
- main-source.yml
- mcp-interface-diff.yml
- mcp-observatory.yml
- mcp-safety-scan.yml
- observatory.yml
- prepare-python-release.yml
- python.yml
- release.yml
- sdk-watch.yml
- typescript.yml
- version-check.yml
- version-packages.yml
- dynamic/agents/copilot-pull-request-reviewer
- dynamic/copilot-pull-request-reviewer/copilot-pull-request-reviewer
- dynamic/copilot-swe-agent/copilot
- dynamic/dependabot/dependabot-updates
- dynamic/dependabot/update-graph
- dynamic/github-code-scanning/codeql

(The GitHub Workflows API reported 24 total workflows.)

---

## 3. Procurement Section

Amazon books search for "Model Context Protocol" — The Amazon search scraper returned `Ok: false` with error `Oxylabs HTTP 429: "Your current plan's quota has been reached."` No result usable; top result title, author, price and rating could not be retrieved. Note: second Amazon query ("Python programming") also failed with the same quota error.

---

## Raw sources (traceability)

- GitHub API data for `modelcontextprotocol/modelcontextprotocol` (stars, open issues, default branch, latest commit SHA/author date) — github_get_commit, github search_repositories.
- Workflows in `modelcontextprotocol/servers` — github_list_workflows.
- MCP documentation source — github_get_file_contents (README.md of modelcontextprotocol/modelcontextprotocol) and modelcontextprotocol.io (https://modelcontextprotocol.io).
- Amazon search — oxylabs_amazon_search_scraper (HTTP 429 quota exceeded; unavailable).
- Web research — oxylabs google search scraper (HTTP 429 quota exceeded; no AI-overview text captured).
