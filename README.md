# Replit Cat — Terminal UI Design

A standalone HTML design prototype for a Replit companion. The interface uses a macOS Terminal window, a zsh-style prompt, a chronological activity log, inline evidence, and an English-speaking ASCII cat.

## Open the design

Open [`index.html`](index.html) in a browser. No build, server, image file, external font, or dependency is needed.

The sample command and activity log explain a proposed product flow. They do not execute shell commands or connect to Replit, OpenAI, or AWS. Entering a different prompt only displays it locally.

## Interactions

- `Enter` submits the preview input; `Shift+Enter` inserts a line break.
- `:evidence on` expands the sample evidence lines.
- `:replay sample` plays the fixed example again.
- `⌘K` or `Ctrl+K` focuses the input.

## Design references

- [Apple Terminal profiles](https://support.apple.com/guide/terminal/use-profiles-to-change-the-look-of-terminal-windows-trml107/mac)
- [Catppuccin Mocha for Terminal.app](https://github.com/catppuccin/Terminal.app/blob/main/themes/catppuccin-mocha.terminal)
- [Pure zsh prompt](https://github.com/sindresorhus/pure)

The layout and interaction code in this repository are a design prototype for Replit Cat.
