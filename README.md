# claude-monitor-web

Landing page for [claude-monitor](https://github.com/cjthompson/claude-monitor) — a terminal dashboard for monitoring, managing, and automating Claude Code sessions, with permission controls, subagent tracking, persistent hand-offs, session rotation, git worktree detection, and a local HTTP API. Supports iTerm2 pane mirroring on macOS and simple tabbed mode on Linux and other terminals.

## Structure

- `index.html` — Single-page static site with inline CSS/JS
- `images/` — Screenshots used on the landing page

## Development

Open `index.html` in a browser. No build step required.

Keep feature descriptions aligned with the application README. Screenshots come from its `docs/screenshots/` directory; the current upstream assets match the local copies. The gallery includes all seven available screenshots (including the hero). There are no upstream hand-off or rotation screenshots yet.

## Deployment

Static site — deploy to any static hosting (GitHub Pages, Netlify, Vercel, etc.).

## License

MIT
