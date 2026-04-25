# Contributing to Web Metronome

Thanks for your interest in improving **Web Metronome**! Contributions of all kinds are welcome — bug reports, feature ideas, documentation fixes, and code.

## Ground Rules

| Rule | Why |
|---|---|
| **Single-file architecture** | The entire app lives in `metronome.html`. Do not split it into separate JS/CSS files. |
| **Zero dependencies** | No npm packages, no CDN links, no frameworks. |
| **Web Audio API only** | All audio must use the Web Audio API (WAA). No `<audio>` element hacks. |
| **Accessible** | Keep keyboard shortcuts working and maintain colour contrast. |

## How to Contribute

1. **Fork** this repository.
2. **Create a branch**: `git checkout -b feat/my-feature`.
3. **Make your changes** in `metronome.html`.
4. **Test** in at least Chrome and Firefox.
5. **Commit** with a clear message: `feat: add swing subdivision`.
6. **Push** to your fork and open a **Pull Request** against `main`.

## Reporting Issues

- Use the GitHub **Issues** tab.
- Include: browser name + version, OS, steps to reproduce, expected vs. actual behaviour.
- Screenshots or screen recordings are very helpful.

## Code Style

- 2-space indentation.
- Use `const` / `let`; avoid `var`.
- Prefer template literals over string concatenation.
- Keep functions short and well-named.

## License

By contributing you agree that your work will be released under the project's [MIT License](LICENSE).
