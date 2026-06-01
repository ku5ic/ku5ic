# Sinisa Kusic

Senior Frontend Engineer with 18 years of experience. I specialize in React, Next.js, and TypeScript, with a strong focus on architecture, performance, accessibility, and long-term maintainability. I work best on complex problems: legacy modernization, scalable component systems, and raising product quality without losing pragmatism.

I also write about frontend engineering and software thinking on [Substack](https://substack.com/@ku5ic) and [Dev.to](https://dev.to/ku5ic).

Available for senior remote roles. [CV](https://ku5ic.github.io/cv/) | [LinkedIn](https://www.linkedin.com/in/sinisakusic/) | [Upwork](https://www.upwork.com/freelancers/~013311f3877ee71207)

---

## Featured projects

### nuka-ui

A production-grade React component library built on Tailwind v4.

It demonstrates component API design under real constraints: a two-layer CSS token architecture for safe theming, composable variant and intent axes that eliminate one-off class combinations, WCAG 2.2 AA compliance enforced from the start, and TypeScript strict mode with the flags most projects disable.

Every architectural decision is documented. The Radix UI dependency was removed in favor of a first-party Slot implementation to make the composition pattern explicit and owned.

Live Storybook: https://ku5ic.github.io/nuka-ui
Repository: https://github.com/ku5ic/nuka-ui

### foxhole

A frontend audit CLI and MCP server that combines Lighthouse, axe-core, a custom semantic checker, and bundle analysis into a single scored report.

The design priority is actionability over numbers. Instead of a raw Lighthouse score, foxhole ranks findings by severity and effort so a failing CI run tells you what to fix first and why. It runs against any URL, local build, or SPA route list, exits non-zero when a score threshold is missed, and produces structured JSON output suitable for diffs across builds.

It also exposes its audit capabilities as MCP tools, making it directly callable from Claude Code and other MCP-compatible agents.

Repository: https://github.com/ku5ic/foxhole

### Battleship

A frontend architecture showcase built with React and TypeScript.

It demonstrates framework-independent domain design, with shared game logic and state transitions powering both the browser UI and a standalone CLI. The project focuses on separation of concerns, derived state, accessibility-first implementation, and structured AI-assisted development with human-owned architectural decisions.

Live demo: https://ku5ic.github.io/battleship/
Repository: https://github.com/ku5ic/battleship

---

## Also

### Dotfiles

macOS development environment built around Neovim, tmux, and zsh. Configured for keyboard-driven workflow, fast navigation, and minimal context switching.

Repository: https://github.com/ku5ic/dotfiles
