# Public Pages

Static public web pages (privacy policies, support/legal pages) for my apps,
hosted free via **GitHub Pages**. One folder per project so a single repo can
serve many apps.

**Live site:** https://brian1x1.github.io/public-readme/

## Projects

| Project | Page | URL |
|---|---|---|
| Gaelic Keepy-Uppy | Privacy policy | https://brian1x1.github.io/public-readme/gaelic-keepy-uppy/ |

## Layout

```
/
├── README.md                 # this file
└── <project-slug>/
    └── index.html            # the project's public page
```

Each project lives in its own folder; the folder name becomes the URL path.
For example `gaelic-keepy-uppy/index.html` is served at
`…/public-readme/gaelic-keepy-uppy/`.

## Adding a new project

1. Create a folder named after the project (e.g. `my-next-app/`).
2. Add an `index.html` inside it.
3. Commit and push to `main` — GitHub Pages rebuilds automatically (usually
   within a minute or two).
4. The page is live at `https://brian1x1.github.io/public-readme/my-next-app/`.

> **Tip:** use that per-project URL as the *Privacy policy URL* in the Google
> Play Console (or App Store Connect) for the matching app.

## Notes

- Pages is served from the `main` branch, root (`/`).
- This is a public repo — don't put anything private here.
- Keep each privacy policy in step with its app: when an app starts storing
  new data, adds a permission or a Google/third-party feature, update its page
  and the *Last updated* date before that build ships, and make sure the Play
  Console Data safety form still matches.
