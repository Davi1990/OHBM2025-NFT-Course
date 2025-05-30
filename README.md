# OHBM 2025 Neural Field Theory Course Website Repo

Welcome.

This is the source code for the OHBM 2025 Neural Field Theory educational course website.

The website is live here: [https://davi1990.github.io/OHBM2025-NFT-Course](https://davi1990.github.io/OHBM2025-NFT-Course)

## For web developers:

### Summary

The website is built with **Hugo** and deployed automatically on the **gh-pages** branch via GitHub Pages.

The site rebuilds on every new commit pushed to this repository.

To see your changes online, wait about 20 seconds after pushing, then refresh the page.

Minor edits can be made directly through the GitHub web editor, but for larger changes, working locally is recommended.

### Using GitHub Codespaces

- Fork this repository.  
- Create a Codespace on your fork.  
- Create a new branch for your edits.  
- To build and preview locally inside the Codespace, run:

  ```bash
  hugo --minify
  cd public
  python3 -m http.server 1313
