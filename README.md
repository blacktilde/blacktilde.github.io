# blacktilde.com

Landing page for blacktilde.com. Projects live on `*.blacktilde.com`.

A single static `index.html` with no build step: a floating nav with a Projects menu and a GitHub
link, and the tilde logo in the centre (it turns into a moving wave on hover).

To add a project, drop its logo in `icons/` and add a line to the list inside the nav in `index.html`:

```html
<li><a href="https://notes.blacktilde.com"><span class="p"><img class="pl" src="icons/notes.svg" alt="">Notes</span><span class="d">Short description</span></a></li>
```

## Icons

- `favicon.svg`: the site favicon
- `icons/logo.svg`: source logo (vector)
- `icons/logo-1024.png`, `icons/logo-512.png`: PNG exports
- `icons/apple-touch-icon.png` (180px), `icons/favicon-32.png`: browser/home-screen icons
- `icons/ping.svg`, `icons/boards.svg`: project logos, from [dbohry/ping](https://github.com/dbohry/ping) and [dbohry/kanban](https://github.com/dbohry/kanban)
- `icons/img.svg`: project logo for img.blacktilde.com
