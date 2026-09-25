# blacktilde.com

Landing page for blacktilde.com. Projects live on `*.blacktilde.com`.

A single static `index.html` with no build step. To add a project, add a line to the
`projects` array near the bottom of `index.html`:

```js
{ sub: "notes", desc: "What it does." },            // links to notes.blacktilde.com
{ sub: "lab",   desc: "Coming soon.", status: "soon" }, // shown greyed out, no link
```

## Icons

- `favicon.svg`: the site favicon
- `icons/logo.svg`: source logo (vector)
- `icons/logo-1024.png`, `icons/logo-512.png`: PNG exports
- `icons/apple-touch-icon.png` (180px), `icons/favicon-32.png`: browser/home-screen icons
