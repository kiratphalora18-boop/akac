# Claude Code prompt: build a third game for this site

You are working inside this project folder. First inspect `main1.html`, `game1.html`, and `game2.html` so you understand the existing visual style, game launch area, controls, and coding conventions. Treat those files as references only; do not overwrite or remove them.

## Goal

Create a polished, original third browser game for this site as `game3.html`, then add a matching third game button beside the existing game links in `main1.html`.

Before coding, briefly decide on a game concept with a clear, satisfying core loop. It should feel at home beside the existing cosmic arcade game and paper-file mystery game, while bringing a genuinely different mechanic. Prefer a short-session game with replay value, easy to understand in the first 20 seconds, and a small amount of story flavor. Do not make another quiz or a reskin of either existing game.

## Game requirements

- Make `game3.html` a complete, standalone game using HTML, CSS, and vanilla JavaScript. No build step, framework, package installation, server dependency, or external game library.
- Give it a memorable title screen, concise instructions, a playable game loop, pause/resume, clear win or game-over feedback, restart, score, and saved best score using `localStorage`.
- Make controls comfortable on desktop and phone: keyboard and/or pointer on desktop, large touch controls or direct touch interaction on mobile. Avoid requiring hover.
- Keep layouts usable in portrait and landscape, account for safe areas, and prevent accidental page scrolling while the player is interacting with the game.
- Use canvas or lightweight DOM rendering where appropriate. If using canvas, handle resize and device pixel ratio safely, cap pixel ratio for performance, use `requestAnimationFrame` with delta time, and stop or pause the loop when the document is hidden.
- Add sound only if it improves the game; it must be optional, start muted, and never play before user interaction.
- Include accessible button labels, visible keyboard focus, readable contrast, and `prefers-reduced-motion` support.
- Create visuals from CSS, canvas, or inline SVG; do not depend on remote image assets. Keep the page fast and self-contained.
- Make the visual design feel like a deliberate sibling to the existing pages. Reuse their warm storybook / evidence-file atmosphere or cosmic arcade energy where appropriate, while giving this game its own identity.

## Integration and care

- Add one clearly labeled game button in the existing game selection area of `main1.html`, linking to `game3.html`. Match the current button style and keep the other links intact.
- Do not change `index.html`, `game1.html`, `game2.html`, or unrelated files.
- Do not claim tests passed unless you actually run them. At minimum, inspect the final files for broken paths and JavaScript errors; if browser tooling is available, launch and play through one full round on desktop and a narrow mobile viewport.
- Keep code readable, use descriptive names, and avoid unnecessary external services or telemetry.

## Finish

When done, summarize the game concept, core controls, files changed, and exactly what you verified. Keep the implementation focused: deliver a fun, finished mini-game, not a large game framework.
