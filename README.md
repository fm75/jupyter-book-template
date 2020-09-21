# jupyter-book-template
Template for jupyter-books using binder

## Edit the org and repo here
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fm75/jupyter-book-template/master?urlpath=lab)

## Edit the URL for pages here
[Docs](https://fm75.github.io/jupyter-book-template/)

## Publishing 
### Using GitHub actions
It will publish to gh-pages on a PR/

### Manually using make in binder
Configure git.
```bash
  git config --global user.email "youremail@example.com"
  git config --global user.name "Your Name"
```
After configuring git, you can use `git commit` and `git push` to push changes back to remote.

You can also publish from within binder
```bash
make build
make publish
```

