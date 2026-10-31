# Burn

A Mac app for keeping an eye on Claude Code usage. It reads the local Claude Code logs and shows your 5-hour and weekly limits, token history by day and project, how to pace the rest of your week, and what your agents are spending. Nothing leaves your Mac.

![Burn](https://github.com/unpaidfunds/burn/releases/download/v1.1-beta/burn-now.png)

## Features

- 5-hour and weekly limits with reset times (exact when you're signed in to Claude Code, estimated otherwise)
- Daily heatmap, weekly bars and all-time totals
- Usage per project and a plan for the rest of the week
- Agent graph with each agent's spend, budget and warnings
- tokenmaxxing: a live view of what Claude Code is doing right now
- Three themes, works in split screen

![tokenmaxxing](https://github.com/unpaidfunds/burn/releases/download/v1.1-beta/burn-tokenmaxxing.png)

<p>
  <img src="https://github.com/unpaidfunds/burn/releases/download/v1.1-beta/burn-history.png" width="49%" alt="History" />
  <img src="https://github.com/unpaidfunds/burn/releases/download/v1.1-beta/burn-agents.png" width="49%" alt="Agents" />
</p>

*Screenshots use sample data.*

## Install

1. Download the `.zip` from the [Releases page](https://github.com/unpaidfunds/burn/releases).
2. Unzip it and drag `Burn.app` into Applications.
3. The app is unsigned. Right-click it, choose **Open**, then confirm. Or run once:

```sh
xattr -cr /Applications/Burn.app
```

Requires an Apple Silicon Mac.

## Beta

Still in beta, so expect rough edges. Bug reports are welcome in Issues.

## License

Personal, non-commercial use only. See [LICENSE](LICENSE).
