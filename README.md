# meet-sujit

My personal page: a career told as a `git log --graph`, where the `ai` branch finally merges into `main`. It's plain HTML and CSS, with no build step.

## Publish on GitHub Pages

1. Create a repo named `BlackRabbitt.github.io`, or any name if you want the page at `/meet-sujit`.
2. Push to `main`.
3. Go to **Settings → Pages → Deploy from a branch**, then pick `main` and `/ (root)`.

## Page layout

1. **hero**: who I am, links, numbers.
2. **`git show HEAD`**: the 30-second version, four impact highlights.
3. **case study**: the event bus, with expandable details.
4. **`git log --graph`**: the full journey, with `main` and `ai` lanes.
5. **projects**, **fortunes**, **postmortems**, **package.json**, **now**.

Open items for review are marked `TODO(sujit)` in HTML comments.

## Edit

- Commits are the `<li class="c ...">` items in `index.html`. Use `main` for the career lane and `ai` for the AI lane. Add `ai-on` to a `main` commit, or `main-on` to an `ai` commit, while both branches are alive.
- To add a fortune, add an `<li>` to `.cookies`. The "another one" button picks it up automatically.
- To add a postmortem, copy a `<details class="pm">` block.
- To add a highlight, copy an `<article class="hl">` block in `#head`. Keep each row to one or two sentences.
