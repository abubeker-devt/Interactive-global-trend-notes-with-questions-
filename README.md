# Global Trends — Interactive Study Notes

A self-contained, static HTML/CSS/JS quiz site covering all 5 units of the Global Trends course, plus a Final Exam practice tab. No backend, no build step — works as-is on GitHub Pages.

## What's inside
- Unit 1–5 tabs: multiple-choice questions (tap an option — green if correct, red if wrong, with an explanation) and "Explain" questions (tap to reveal a model answer).
- Final Exam tab: practice MCQs and explain questions.

## How to publish on GitHub Pages
1. Create a new GitHub repository (public).
2. Upload `index.html` to the root of the repo (this zip is already structured that way — just drag the extracted files in, or upload the zip's contents).
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main` (or `master`), folder `/ (root)`.
5. Save. GitHub will give you a live URL like `https://yourusername.github.io/repo-name/` within a minute or two.

## Editing content
All questions live in a single JSON object near the top of the `<script>` tag in `index.html`. Each chapter has an `mcq` array (`q`, `o` options, `a` correct index, `e` explanation) and an `explain` array (`q`, `a` answer). Edit directly and re-upload to update the site.
