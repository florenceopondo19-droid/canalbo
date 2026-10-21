# Canalbox RDC

This repository contains the standalone Canalbox static site.

## Deploy on Render

1. Push the contents of this folder to the GitHub repository `canalbox-rdc`.
2. In Render, create a **Static Site** and connect that repository, or create a
   Blueprint from its `render.yaml`.
3. If configuring the site manually, set the build command to blank and the
   publish directory to `.`.
4. Deploy. The site is served from `index.html`.
