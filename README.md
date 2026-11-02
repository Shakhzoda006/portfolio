# Portfolio site

A single-page portfolio: `index.html` plus `images/` and `videos/`. No build step.

## Before you publish

1. **Open `index.html` in a text editor** and scroll to the bottom. Fill in:
   - `github`: your GitHub username
   - `cv`: the file name of your CV PDF (put the PDF in this folder, e.g. `cv.pdf`)
   - `devmatchRepo`: the link to your own fork of DevMatch, if you make one

   Anything left blank is hidden automatically.

2. **Add DevMatch screenshots** (optional, but they help a lot). Save them in `images/` with exactly these names:

   | File name | What it should show |
   |---|---|
   | `devmatch-1.jpg` | The dashboard |
   | `devmatch-2.jpg` | A developer profile |
   | `devmatch-3.jpg` | Offers / applications |

   Any screenshot you don't add simply won't appear. If a screenshot shows the
   wrong thing, change its caption in `index.html` (search for `devmatch-1`).

3. **Check what's public.** The site shows your KAIST email, but no phone number,
   address, or student ID. Keep it that way.

## Put it on GitHub Pages

1. Create a new repository named `<your-username>.github.io`.
2. Upload everything in this folder (`index.html`, `images/`, `videos/`, and your CV).
3. In the repository, open Settings → Pages, set the source to the `main` branch, root folder.
4. After a minute, the site is live at `https://<your-username>.github.io`.

## Editing later

All text is in `index.html`. Each project is one `<article>` block, so you can
copy one to add a new project (for example, your HCI project once it's done).
