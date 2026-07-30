# mbusch1.github.io

Personal academic website for Michael P. Busch, Jansky Postdoctoral Fellow at NRAO.
Live at <https://mbusch1.github.io>.

Built on [AcademicPages](https://github.com/academicpages/academicpages.github.io), a Jekyll
template forked from [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/).

## Editing the site

Everything you'd normally change is content, not code:

| What | Where |
|---|---|
| Your name, email, sidebar links, ORCID, CV link | `_config.yml` (the `author:` block) |
| Nav bar tabs and their order | `_data/navigation.yml` |
| About / Research / Students pages | `_pages/about.md`, `research.md`, `students.md` |
| A new paper | one new file in `_publications/` — copy an existing one |
| A paper that's accepted but not yet published | add `accepted: true` to its front matter; the page then says "Accepted for publication in …" instead of "Published in …". Remove it once the paper appears, and swap `paperurl` from arXiv to the journal DOI |
| A new talk | one new file in `_talks/` |
| A new blog post | one new file in `_posts/`, named `YYYY-MM-DD-slug.md` |
| Images | `images/` |
| CV PDF | `files/cv.pdf` |

Search the repo for `TODO(Michael)` to find every spot that still needs your input:

```bash
grep -rn "TODO(Michael)" --exclude-dir=.git .
```

## Previewing locally

```bash
bundle install          # first time only
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000>. Markdown and HTML changes reload automatically;
**changes to `_config.yml` require restarting the server.**

## Publishing

Push to `main`. GitHub Pages rebuilds and deploys automatically, usually within a minute.

```bash
git add -A && git commit -m "Add a paper" && git push
```
