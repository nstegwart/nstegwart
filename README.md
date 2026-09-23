# Gian Rhamadhan

Software engineer · Jakarta, Indonesia

I build mobile and web products end to end, from the Figma file to the backend, the infrastructure, and the app in the store.

Most of that work is done by fleets of AI coding agents running in parallel. I orchestrate them, benchmark the models behind them, and build the tooling that holds the whole system together.

## How I work

After more than 4,000 agent sessions, I treat AI coding agents as a team to orchestrate. They are not a single copilot I prompt one request at a time.

- **Parallel fleets.** Many agents run at once, each in its own git worktree, so independent pieces of work move forward at the same time without colliding.
- **Multiple harnesses.** I use Claude Code, Codex, opencode and others side by side, and I pick the harness for each task instead of committing to one.
- **Head-to-head benchmarks.** I give different models the same task in the same repository and compare what they produce. The results decide which model handles which kind of work.
- **Tooling I build myself.** I write model routers, MCP servers, agent skills, and prompt-dispatch systems that turn one instruction into coordinated work across many agents. One of these is a local Figma MCP server that lets agents read and build directly in design files.

Most of the engineering effort goes into three things: breaking work down so it can run in parallel, matching each task to the right model, and judging what comes back.

## What I build

- **Mobile:** React Native and Expo. Apps shipped to the App Store and Google Play, with over-the-air update pipelines for releasing fixes between store builds.
- **Web:** React and Next.js. I do new builds and modernize legacy code, including bringing Node 12-era codebases up to current versions.
- **Backend:** PHP (Laravel), Node.js/Express, Go, and Rust. REST APIs, queue workers, and schedulers.
- **Infrastructure:** Google Cloud across multiple projects, MySQL, Redis, and Docker. Self-hosted CI runners on GitHub Actions and GitLab CI.
- **Design:** Figma-driven product design, design systems, and art direction for app store listings.
- **Automation:** Content and data pipelines for scraping, scheduled digests, and publishing.

**Languages:** TypeScript / JavaScript, PHP, Go, Rust, Python, shell

## Currently

Shipping mobile, web, and backend product work, and improving the routing and dispatch tooling behind my agent fleets.

## Contact

X / Twitter: [@wdyhere](https://x.com/wdyhere)
