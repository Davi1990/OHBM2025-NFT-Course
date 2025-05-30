# BrainModes 2025 Conference Website Repo

Welcome friend.

This is the website source for the BrainModes 2025 conference

The conference website can be viewed [here](https://griffithslab.github.io/BrainModes2025).

## For webdevs:

### Summary

The website is written in Hugo and deployed with CI on gh-pages

The site will re-build upon each new commit to this repo. 

To see changes, wait 20 secs or so, and then refresh the page. 

The github text editor should be sufficient for minor changes. 

In general however, best to work on a local clone. 

Github codespaces works very well for this. 

### Github Codespaces 

- Fork this repo
- Create a codespace on it
- Make a git branch for current edits
- To test review the build after making some changes:
  ```bash
  hugo --minify
  cd public
  python -m http.server
  ```
- when you're satisfied, commit and pull request on your branch



### Structure: 

- Landing page and title are specified in config.toml

- Main pages are specified in 'content' folder

- Text is mostly written in markdown


