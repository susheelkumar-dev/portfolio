# Susheel Kumar — Portfolio

One static file: `index.html`. No build step, no Node, no framework. Open it in a browser and it works.

## Before you publish (5 minutes)

Open `index.html` and find the `CONFIG` block near the top of the `<script>`:

```js
const CONFIG = {
  email:    'susheelkumar.mca@gmail.com',
  linkedin: '',   // your LinkedIn URL
  github:   '',   // your GitHub profile URL
  resume:   ''    // 'resume.pdf' after you put the PDF next to index.html
};
```

Empty values hide their buttons, so nothing broken ever shows.

Then, in the `PROJECTS` list just below it:

- Add `links: { demo: 'https://…', repo: 'https://github.com/…' }` for each project you can share. GridTrade Lite's AWS URL goes in `demo`.
- Add the real feature list for the Ext JS grid project (sorting, grouping, editing, etc.).
- Check the career phase wording in the `#career` section of the HTML.

## Deep links

`yoursite/#gridtrade` opens the GridTrade Lite case study directly. Other ids: `migration`, `grid`, `agents`, `dotnetmicro`, `strangler`. Useful in job applications.

## Free hosting

**GitHub Pages:** create a repo, upload `index.html` (and `resume.pdf`), then Settings → Pages → Deploy from branch → `main` / root. Site appears at `https://<username>.github.io/<repo>/`. Name the repo `<username>.github.io` to get the root URL.

**Cloudflare Pages / Netlify:** drag the folder onto the "deploy manually" upload box. No build command, output directory `/`.

## Keyboard

`/` or `Ctrl+K` opens quick search. Arrow keys move through the domain tabs.
