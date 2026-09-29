# alexanderdenes.com — instructions for Claude

This is Alexander Denes's personal essay site: plain HTML + one CSS file, no build step.
It's hosted on GitHub Pages; pushing to the main branch publishes it live.

## Adding an essay
1. Copy `essays/_template.html` to `essays/<short-slug>.html` (lowercase, hyphens).
2. Fill in the title (in both <title> and <h1>), the date (Month Year), and the text as <p> paragraphs.
3. Add a line at the TOP of the essay list in `index.html`:
   `<li><a href="/essays/<slug>.html">Title</a> <time datetime="YYYY-MM">Month YYYY</time></li>`
4. Commit with a clear message and push.

## Editing an essay
Edit the file in `essays/`. If the title changes, update it in `index.html` too. Commit and push.

## Rules
- Keep the design minimal. Don't add frameworks, scripts, trackers, or new fonts unless asked.
- Preserve Alex's wording; only fix typos or restructure if he asks.
- Never delete an essay without confirming first.
