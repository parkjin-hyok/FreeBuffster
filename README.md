# Freebuff

English | [简体中文](./README.zh-CN.md)

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=flat-square)](https://www.typescriptlang.org/)
[![Bun](https://img.shields.io/badge/Bun-000000?logo=bun&logoColor=white&style=flat-square)](https://bun.sh/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white&style=flat-square)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black&style=flat-square)](https://react.dev/)
[![OpenTUI](https://img.shields.io/badge/OpenTUI-5B5BD6?logo=opentui&logoColor=white&style=flat-square)](https://opentui.dev/)
[![MIT License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://opensource.org/licenses/MIT)
[![GitHub Repo Stars](https://img.shields.io/github/stars/sketchie-durk/Buffster?style=flat-square)](https://github.com/sketchie-durk/Buffster/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/sketchie-durk/Buffster?style=flat-square)](https://github.com/sketchie-durk/Buffster/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/sketchie-durk/Buffster?style=flat-square)](https://github.com/sketchie-durk/Buffster/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/sketchie-durk/Buffster?style=flat-square)](https://github.com/sketchie-durk/Buffster/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/sketchie-durk/Buffster?style=flat-square)](https://github.com/sketchie-durk/Buffster/commits)
[![Release](https://img.shields.io/github/v/release/sketchie-durk/Buffster?style=flat-square)](https://github.com/sketchie-durk/Buffster/releases)
[![Contributors](https://img.shields.io/github/contributors/sketchie-durk/Buffster?style=flat-square)](https://github.com/sketchie-durk/Buffster/graphs/contributors)
[![Repo Size](https://img.shields.io/github/repo-size/sketchie-durk/Buffster?style=flat-square)](https://github.com/sketchie-durk/Buffster)
[![Code Size](https://img.shields.io/github/languages/code-size/sketchie-durk/Buffster?style=flat-square)](https://github.com/sketchie-durk/Buffster)
[![Website](https://img.shields.io/badge/Website-Freebuff-0A66C2?style=flat-square)](https://freebuff.com)
[![Docs](https://img.shields.io/badge/Docs-Available-0A66C2?style=flat-square)](https://freebuff.com/docs)
[![Open Source](https://img.shields.io/badge/Open%20Source-Yes-21BA45?style=flat-square)](https://opensource.org/)
[![CI](https://img.shields.io/badge/CI-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white&style=flat-square)](https://github.com/sketchie-durk/Buffster/actions)
[![Testing](https://img.shields.io/badge/Testing-Automated-FF6B6B?style=flat-square)](https://github.com/sketchie-durk/Buffster/actions)
[![Type Safety](https://img.shields.io/badge/Type%20Safety-Strict-3178C6?style=flat-square)](https://www.typescriptlang.org/)
[![Linting](https://img.shields.io/badge/Linting-ESLint-4B32C3?logo=eslint&logoColor=white&style=flat-square)](https://eslint.org/)
[![Package](https://img.shields.io/badge/Package-Freebuff-7C3AED?style=flat-square)](https://www.npmjs.com/package/freebuff)
[![Downloads](https://img.shields.io/npm/dm/freebuff?style=flat-square)](https://www.npmjs.com/package/freebuff)
[![Support](https://img.shields.io/badge/Support-Community-5865F2?logo=discord&logoColor=white&style=flat-square)](https://discord.gg/yXG3w7wxfs)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?logo=discord&logoColor=white&style=flat-square)](https://discord.gg/yXG3w7wxfs)
[![Security](https://img.shields.io/badge/Security-Reviewed-2E7D32?style=flat-square)](https://github.com/sketchie-durk/Buffster/security)
[![Architecture](https://img.shields.io/badge/Architecture-Multi%20Agent-FFB300?style=flat-square)](https://github.com/sketchie-durk/Buffster)
[![Community](https://img.shields.io/badge/Community-Active-1D4ED8?style=flat-square)](https://github.com/sketchie-durk/Buffster/discussions)
[![Code Quality](https://img.shields.io/badge/Code%20Quality-High-F59E0B?style=flat-square)](https://github.com/sketchie-durk/Buffster)

**Five free AI products for coding, building, and research.** No subscription, credits, or API key required.

[Freebuff](https://freebuff.com) brings specialized agents and a choice of leading models to your terminal, desktop, browser, and GitHub repositories. Text ads support access to the included models, and the app shows which model each session uses. Looking for the browser app or desktop app? Those products are loaded from a bundled client in this repo.

## Choose your Freebuff

| Product              | What it does                        | Get started                                                           |
| -------------------- | ----------------------------------- | --------------------------------------------------------------------- |
| **Freebuff Desktop** | Run parallel agents locally         | [Download for macOS, Windows, or Linux](https://freebuff.com/desktop) |
| **Freebuff CLI**     | Code from your terminal             | [Install the CLI](https://freebuff.com/cli)                           |
| **Freebuff Web**     | Build and ship full-stack apps      | [Build an app](https://freebuff.com/web)                              |
| **Freebuff Cloud**   | Run agents on any GitHub repository | [Connect a repository](https://freebuff.com/cloud)                    |
| **Freebuff Chat**    | Research and think with AI          | [Start a chat](https://freebuff.com/chat)                             |

## Quick start

Run Freebuff in any project from your terminal:

```bash
npm install -g freebuff
cd ~/my-project
freebuff
```

Then describe what you want. Freebuff finds the relevant files, makes changes, and runs the checks that matter for your project.

## Models

Freebuff includes a curated model catalog. The regular picker currently offers:

| Model                       | Access                  | Best for                                                          |
| --------------------------- | ----------------------- | ----------------------------------------------------------------- |
| **MiMo v2.6 Flash Fast**    | Full and limited access | The default everywhere; balanced performance with image support   |
| **GLM 5.3 Flash**           | Full and limited access | Deepest reasoning                                                 |
| **DeepSeek V4.1 Flash 10/17** | Full and limited access | Fast coding and tool use                                          |
| **DeepSeek V4.1 Flash Fast 10/17** | Full access; paid plans at limited access | Fast mode: the same model on DeepSeek's own API, splitting work across parallel subagents and verifying the result |
| **GPT-6 Luna**              | Full access             | Strong all-around with native images; runs on OpenAI flex capacity |
| **MiMo 2.6 Pro**            | Full access             | Xiaomi's stronger reasoning model, with image support |
| **Solar Mini 4**            | Full and limited access | Upstage's fast, compact model; 524K context, text only |
| **Solar Pro 4**             | Full and limited access | Upstage's larger, stronger model; 524K context, text only |
| **Gemini 3.8 Flash**        | Paid plans              | 1M context, and the only model that accepts audio, video and PDF |
| **Muse Spark 1.3**          | Paid plans              | Meta's agentic coding model; 1M context. When it is busy or unavailable, it answers on DeepSeek V4.1 Flash rather than making you wait |
| **Gemini 4 Argon**          | US, or paid plans elsewhere | Google's flagship reasoning model, one session a day for every account; 1M context, images |
| **GPT-6.1 Terra**           | Full access; paid plans at limited access | OpenAI's model at a temporary promotional price, one session a day for every account; 1M context, images |
| **GPT-6.1 Sol**             | US, or paid plans elsewhere | OpenAI's flagship, one session a day for every account; 1M context, images |

Prices change often, so this README does not list them: the model picker shows what each model costs as a multiplier. An hour on a 1x model uses one hour of your balance, an hour on a 3x model uses three hours, and the same model costs more or less depending on your access tier and current service availability.

DeepSeek V4 Pro was retired from the catalog; GLM 5.3 Flash replaces it as the deep-reasoning pick.

Beyond the regular picker:

- **Referrals and bounties** earn extra hours on top of the free daily allowance.
- **Gemini 3.1 Flash Lite** powers specialist tasks such as file finding and research rather than appearing in the main picker.

Availability and limits depend on your access tier, product, and current capacity. Freebuff Desktop can also run locally installed Claude Code and Codex agents using your existing provider account and token balance.

## How Freebuff works

Freebuff uses specialized agents instead of sending every task through one model and one prompt. Depending on the task, agents gather context, plan, edit or research, run tools, and review the result before presenting it back to you.

- **Codebase context** — File-finding agents map the relevant parts of a project before editing.
- **Implementation and review** — Agents can divide work, make changes, run commands, and inspect the result.
- **Research and browser use** — Agents can investigate documentation and test applications in a real browser.
- **Parallel local work** — Desktop isolates concurrent agents in separate workspaces.
- **Hosted environments** — Web and Cloud provide sandboxes, previews, terminals, and deployment workflows.

## Free access

Freebuff is available in every country. Supported regions receive full access; other regions and VPN users receive limited access to GLM 5.3 Flash, DeepSeek V4.1 Flash 10/17, MiMo v2.6 Flash Fast, and other models with a reduced balance or priority cap. The app also offers referral-boosted access and usage limits that vary by region and product.

Text ads support the included models. Freebuff shows the applicable session limits and any model-specific data-use notice before you start.

<!-- BEGIN GENERATED FREEBUFF DATA USE -->

**Is my data used to train AI?** Only when a model or feature says data may be used for AI training. Freebuff or the provider may then keep submissions to develop, train, test, evaluate, fine-tune, and improve AI systems.

**How is my data used and stored?** Freebuff uses your messages, agent traces, and files to run the service and respond to your requests. We may analyze this data, and how you use the app, to personalize product features, monitor security and abuse, and improve quality and performance.

**Does Freebuff read files outside my project?** No, with a few exceptions, such as files an agent reads in the conversation, files you share, and settings like your agent instructions and skills.

See the [Privacy Policy](https://freebuff.com/privacy-policy) for complete details.

<!-- END GENERATED FREEBUFF DATA USE -->

## Contributing

Freebuff is a TypeScript monorepo built with Bun. Contributions to the products, agents, tools, documentation, and underlying runtime are welcome.

Local development requires Docker and a configured `.env.local`; see the
[Contributing Guide](./CONTRIBUTING.md) before starting the services.

```bash
git clone https://github.com/CodebuffAI/freebuff.git
cd freebuff
bun install
bun up
```

Start the CLI separately with:

```bash
bun start-cli
```

See the [Contributing Guide](./CONTRIBUTING.md), [development guide](./docs/development.md), and [testing guide](./docs/testing.md) for environment setup and the checks to run before opening a pull request.

## Built on Codebuff

Freebuff is built on [Codebuff](https://codebuff.com), the open multi-agent framework that powers its orchestration, tools, and SDK. To create custom agents or embed them in another application, explore the Codebuff open-source libraries and documentation.

## Links

- [Website](https://freebuff.com)
- [GitHub](https://github.com/CodebuffAI/freebuff)
- [Discord](https://discord.gg/yXG3w7wxfs)
- [Privacy Policy](https://freebuff.com/privacy-policy)
- [License](./LICENSE)
