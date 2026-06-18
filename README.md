# Ship Log

A public, dated record of things I finish and put in the world. One link per ship. No drafts.

This exists to fix one specific problem: building a lot, shipping little. The log makes shipping **visible** — every entry needs a link a stranger can open, so the bar is "out the door," not "feature-complete."

## What it is NOT

- Not a blog or a CMS. No build step, no generator, no dependencies.
- Not a backlog or a roadmap. Only finished things go here.
- Not a system to maintain. One HTML file. If maintaining it ever feels like a project, it has failed.

## Stack

| Layer | Choice | Why |
|---|---|---|
| Everything | A single `index.html` | Zero build, zero deps, opens anywhere, renders in 1 file |
| Hosting | GitHub Pages | Free, public URL, ships on push |
| Theming | CSS variables | Retheme by swapping vars, never touching markup |

## Add a ship

Open `index.html`, find the `SHIPS` array near the bottom, add one object to the top:

```js
{
  date: "2026-06-20",
  title: "Name of the thing",
  body:  "One or two sentences. What shipped, why it counts.",
  link:  "https://...",     // optional — the proof
  tags:  ["cli", "python"]  // optional
}
```

Save, commit, push. The push is the ship.

## The rule

An entry only goes here once a stranger can open the result. That constraint is the entire value of the project.

## License

MIT — © 2026 Yash Shrivardhan Kar
