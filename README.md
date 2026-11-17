# Lucy in Love — encrypted strategy site

This repository publishes an encrypted static artifact to GitHub Pages.

- `site/index.html` contains ciphertext and the browser-side password form.
- The readable strategy source and password are not stored in this repository.
- GitHub Actions deploys only the contents of `site/`.

The page was encrypted with [StatiCrypt](https://github.com/robinmoisson/staticrypt), using AES-256 through the Web Crypto API.
