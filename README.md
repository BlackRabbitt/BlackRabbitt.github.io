# meet-sujit

My personal page: a career told as a `git log --graph`, where the `ai` branch finally merges into `main`. It's plain HTML and CSS, with no build step.

## Publish on GitHub Pages

1. Create a repo named `BlackRabbitt.github.io`, or any name if you want the page at `/meet-sujit`.
2. Push to `main`.
3. Go to **Settings → Pages → Deploy from a branch**, then pick `main` and `/ (root)`.

## Page layout

1. **hero**: who I am, links.
2. **impact** (`git show HEAD --stat`): four themes, about 170 words.
3. **career** (`git log --graph`): the full journey, with `main` and `ai` lanes.
4. **case study**: the event bus, with its contract and constraints visible and the details expandable.
5. **projects**, **fortunes**, **postmortems**, **tools**, **now**.

Old anchors `#head`, `#log`, `#readme` and `#deps` still work as aliases.

## Edit

- Commits are the `<li class="c ...">` items in `index.html`. Use `main` for the career lane and `ai` for the AI lane. Add `ai-on` to a `main` commit, or `main-on` to an `ai` commit, while both branches are alive. The `lancerbooks` lane uses `lb`, with `lb-fork` on its first commit and `lb-end` on its last.
- To add a fortune, add an `<li>` to `.cookies`. The "another one" button picks it up automatically.
- To add a postmortem, copy a `<details class="pm">` block.
- To add an impact row, copy a `<div class="stat-row">` block in `#impact`. Keep each row to two or three sentences.
