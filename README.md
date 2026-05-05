# btc/claude-plugins

A small Claude Code plugin marketplace. Currently hosts a single plugin: a fork of [obra/superpowers](https://github.com/obra/superpowers) with a `burndown-reviews` skill that adds multi-model subagent review at the spec, plan, and impl checkpoints.

## Install

```text
/plugin marketplace add btc/claude-plugins
/plugin install superpowers@btc-plugins
```

If you currently have upstream superpowers installed, uninstall it first:

```text
/plugin uninstall superpowers@claude-plugins-official
```

## Source

The fork lives at https://github.com/btc/superpowers on `main`.
