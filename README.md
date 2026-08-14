# What to Edit Next — Project Page

Static GitHub Pages website for:

> **What to Edit Next: Visually Aligned Image-Editing Follow-Up Suggestions in
> Conversational Systems**

**Project lead:** Jinpeng Yu

This repository contains the official project page, the public paper, research
figures, experimental results, and interactive presentation components. It is
a static HTML/CSS/JavaScript site with no build step or package dependencies.

## Structure

```text
index.html                       # Project page content
css/style.css                    # Site layout and paper-specific components
js/main.js                       # Tabs, lightbox, BibTeX, progress, navigation
assets/paper.pdf                 # Public arXiv technical report
assets/figures/teaser.png        # Product motivation figure
assets/figures/framework.png     # Three-stage framework
assets/figures/data-pipeline.png # SFT data construction
assets/figures/source-target.webp # Optimized verifier examples
.nojekyll                        # Disable Jekyll processing on GitHub Pages
```

## Preview locally

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000/`.

## Deploy to GitHub Pages

Push this directory as the root of a GitHub repository. In the repository,
select **Settings → Pages → Deploy from a branch → main / root**. The page will
be published at:

```text
https://<username>.github.io/<repository>/
```

All paper assets use relative paths and work under a repository subpath.

## Public paper

The public paper and citation metadata are available at
[arXiv:2608.07565](https://arxiv.org/abs/2608.07565). The PDF provided on the
project page is the public arXiv technical report.
