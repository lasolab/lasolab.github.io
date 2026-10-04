# LASO Lab website

Source for **https://lasolab.github.io** — built with [Quarto](https://quarto.org) and published automatically by GitHub Actions every time a change is pushed to `main`. You never need to build it yourself.

## Where things live

| To change…                                  | Edit this file                         |
|---------------------------------------------|----------------------------------------|
| The "Now recruiting" banner, menu, footer   | `_quarto.yml`                          |
| Home page                                   | `index.qmd`                            |
| Openings (M.A. post in English and Spanish, undergrads) | `join.qmd`                 |
| Projects                                    | `research.qmd`                         |
| Bio, students, collaborators                | `people.qmd`                           |
| Publications                                | `publications.qmd`                     |
| Courses                                     | `teaching.qmd`                         |
| Colours and fonts                           | `styles.scss`                          |
| Photos                                      | `images/` (keep them under ~500 KB)    |
| CV                                          | `files/Laso_CV.pdf` (no home address!) |

## Common edits

**Add a publication** — in `publications.qmd`, copy one block that starts with `- [`, paste it at the top of its section and change the text. Put your name in `**double asterisks**` to bold it.

**Add a student** — in `people.qmd`, replace the "Could this be you?" box with their name, role and (with their permission) a photo in `images/`.

**Turn the recruiting banner off** — in `_quarto.yml`, delete the `announcement:` block (or change its text for the next cycle).

**Quick fixes in the browser** — on github.com, open a file, click the pencil icon, edit, then "Commit changes". The site updates in about two minutes (watch the *Actions* tab).

## Preview on your own computer (optional)

Install Quarto, open this folder in a terminal and run `quarto preview`.
