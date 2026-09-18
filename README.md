# Getting Paid From Abroad — Zimbabwe

A tool by **Launch Tide Digital** for freelancers in Zimbabwe: which payment routes may
work for a payment from abroad, roughly what each one costs, how long the money takes
to become usable, and what you need to open it. It also shows what does not apply.

General information only — not tax, legal or financial advice.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The entire website in one self-contained file. All styles, scripts and the favicon are inlined. |
| `404.html` | Same file, so any unknown path still opens the tool instead of a GitHub error page. |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is rather than running Jekyll. |

There are no other assets. Nothing loads from this repository except these files.

## Publishing on GitHub Pages

1. Create a **public** repository — `getting-paid-from-abroad` is the name this was built for.
2. Upload the contents of this folder to the root of the `main` branch
   (**Add file → Upload files**, drag all four items in, Commit). `index.html` must sit at
   the repository root, not inside a subfolder.
3. **Settings → Pages** → Source: *Deploy from a branch*, Branch: `main`, Folder: `/ (root)`, Save.
4. The site publishes in a minute or two at:

   `https://<your-username>.github.io/getting-paid-from-abroad/`

If `.nojekyll` does not appear after upload, the browser may have hidden it as a dotfile —
create it in the repository with **Add file → Create new file**, name it `.nojekyll`, and
commit it empty.

## Before this is treated as live

- Every fee, time, requirement and verification date in the build is **illustrative sample
  data**. Replace with checked figures first.
- The feedback form does not post anywhere yet; it needs an endpoint.
- Contact addresses are placeholders and need confirming.
- The privacy notice and terms still need writing.
- The two Google Fonts load from their CDN. To ship with zero webfont bytes, switch the
  design system to its system font stack.
- The **For review** bar at the top of the page is a review aid. Turn it off before launch.

Prototype build, 18 September 2026.
