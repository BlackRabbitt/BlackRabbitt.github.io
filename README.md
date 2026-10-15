# meet-sujit

My personal page: a career told as a `git log --graph`, where the `ai` branch finally merges into `main`. It's plain HTML and CSS, with no build step.

## Publish on GitHub Pages

1. Create a repo named `BlackRabbitt.github.io`, or any name if you want the page at `/meet-sujit`.
2. Push to `main`.
3. Go to **Settings → Pages → Deploy from a branch**, then pick `main` and `/ (root)`.

## Edit

- Commits are the `<li class="c ...">` items in `index.html`. Use `main` for the career lane and `ai` for the AI lane. Add `ai-on` to a `main` commit, or `main-on` to an `ai` commit, while both branches are alive.
- To add a fortune, add an `<li>` to `.cookies`. The "another one" button picks it up automatically.
- To add a postmortem, copy a `<details class="pm">` block.
