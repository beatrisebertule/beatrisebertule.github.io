# My personal website

A simple personal site (About · Experience · Hobbies · CV) built with Jekyll and
deployed automatically to **GitHub Pages** by a GitHub Actions workflow.

## Put it online (5 minutes)

1. **Create a repo** on GitHub named `<your-username>.github.io`
   (then your site lives at `https://<your-username>.github.io`).
   Any other name works too — see the `baseurl` note below.
2. **Upload these files** to the repo (drag-and-drop in the GitHub web UI, or `git push`).
   Make sure the `.github/workflows/pages.yml` file is included.
3. In the repo go to **Settings → Pages → Build and deployment → Source** and choose
   **GitHub Actions**.
4. Open the **Actions** tab — the "Deploy site to GitHub Pages" workflow runs on every
   push to `main`. When it turns green, your site is live.

## Make it yours

| What                         | Where                                  |
|------------------------------|----------------------------------------|
| Name, tagline, email, links  | `_config.yml`                          |
| "Who I am" text              | `index.md`                             |
| Jobs, education, interests   | `experience.md`                        |
| Hobbies                      | `hobbies.md`                           |
| CV PDF                       | replace `assets/cv.pdf` with your own  |
| Profile photo                | add `assets/img/avatar.jpg` and change the path in `index.md` |
| Colours & fonts              | top of `assets/css/style.css`          |

**baseurl:** if the repo is *not* named `<username>.github.io` (e.g. it's called
`website`), set `baseurl: "/website"` in `_config.yml`, otherwise CSS and links break.

## Add another page

Create e.g. `projects.md`:

```markdown
---
layout: default
title: Projects
---

# Projects
...
```

and add it to the `nav:` list in `_config.yml`.

## Preview locally (optional)

```bash
gem install bundler jekyll
jekyll serve
# open http://localhost:4000
```
