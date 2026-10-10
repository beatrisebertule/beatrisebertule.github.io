# My website

A simple personal site (About · Experience · Hobbies · CV) built with Jekyll and
deployed automatically to **GitHub Pages** by a GitHub Actions workflow.

## TODO: change

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
