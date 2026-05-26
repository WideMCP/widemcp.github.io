# WideMCP

**Production MCP servers that actually work.**

WideMCP is an open-source, **local-first** platform for curated [Model Context Protocol (MCP)](https://modelcontextprotocol.io) servers and orchestration around widely used open-source tools. We care about reliability, clear documentation, and privacy—**your workloads run on your machine**; nothing is sent to WideMCP to “do the work” for you.

## Principles

- **Local-first** — tools run where you run them  
- **Privacy-first** — you control data and execution  
- **Production-quality** — tested, documented paths over demos  
- **Open source** — inspect, fork, improve  
- **Human-controlled actions** — explicit consent for installs and risky operations  

## Repositories

| Repo | Role |
|------|------|
| **[WideMCP/widemcp](https://github.com/WideMCP/widemcp)** | **Source code** — monorepo for MCP servers and shared libraries (e.g. `@widemcp/av-server`, `@widemcp/shared`). **Issues, PRs, and CI** live here. |
| **[WideMCP/widemcp.github.io](https://github.com/WideMCP/widemcp.github.io)** (this repo) | **Website** — content for **[widemcp.dev](https://widemcp.dev/)** via GitHub Pages (`CNAME`). |

If you want to **run or contribute to the servers**, start with the **widemcp** repo, not this one.

## Initial focus

- **Audio / video** processing and helpers (first server: **AV / `widemcp-av`**)  
- **Home automation** (planned catalogue direction)  

## Project status

We are **actively building** the first public MCP servers in **[WideMCP/widemcp](https://github.com/WideMCP/widemcp)** — including a local **stdio** server with tools such as **`echo`** and **`get_media_info`** (via **`yt-dlp`** where installed), shared utilities, and **GitHub Actions** on pull requests.

**Quick links**

- **Site:** [widemcp.dev](https://widemcp.dev/)  
- **Code & contributing:** [github.com/WideMCP/widemcp](https://github.com/WideMCP/widemcp) — clone, `npm ci`, `npm run ci`, then follow that repo’s README for MCP client setup (e.g. Claude Desktop, Cursor).  

Contributions are welcome via **fork** and **pull request** into `main` on the **widemcp** repo; merges are done by maintainers after review and green CI.

## License

Apache-2.0 — see [`LICENSE`](LICENSE). (This repository contains the website content for widemcp.dev.)
