# Hamza Khan — Portfolio

Open `index.html` in any browser to view the site. Everything (styles, logos, scripts) is built into that one file.

## Files
- `index.html` — the website
- `resume.pdf` — downloaded by the "Resume" button (replace it with a newer PDF anytime, keeping the same name)

## Adding your links
Open `index.html` in a text editor, scroll to the bottom, and find the `LINKS` block:

```js
const LINKS = {
  resume:              "resume.pdf",
  linkedin:            "",   // https://www.linkedin.com/in/your-handle
  github:              "",   // https://github.com/your-username
  safevisionDemo:      "",   // SafeVision live app
  safevisionGithub:    "",   // SafeVision repo
  customerIntelDemo:   "",   // Customer Intelligence live app
  customerIntelGithub: ""    // Customer Intelligence repo
};
```

Paste each URL between the quotes and save. Any link left empty shows as a greyed-out button.

## Putting it online (free)
- **GitHub Pages:** create a repo, upload `index.html` and `resume.pdf`, then turn on Pages under Settings → Pages.
- **Netlify:** drag this folder onto app.netlify.com/drop.
- **Vercel:** import the repo at vercel.com/new.
