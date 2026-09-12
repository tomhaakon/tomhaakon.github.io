# tomhaakon.github.io

Personal site and game-dev blog, published via GitHub Pages.

- `index.html` — generated blog feed, built from the devlog READMEs listed
  in `projects.json` (currently [pebble-wars-progress-blog](https://github.com/tomhaakon/pebble-wars-progress-blog)).
  Do not hand-edit; it's overwritten by the build.
- `old-projects.html` — archive of earlier, non-blog projects.
- `build.mjs` — regenerates `index.html`. Run `node build.mjs` locally, or
  let the `build.yml` GitHub Action do it on a schedule.
- To add a new game/project to the blog, append it to `projects.json`
  (needs `name`, `repo`, `branch`, `readme`).
