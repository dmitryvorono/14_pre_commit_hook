# Pre-commit hook

This project demonstrate git pre-commit hook. Pre-commit hook is a convenient tool whick allows run some checks before commit and cancel commit if something went wrong.

# How to install

To enable a hook script, put a file `pre-commit` from project folder to `.git/hooks`. Note file should be executable and without any extension.

# Launch

For illustration change any file, e.g. `README.MD` and try to commit:

```bash
$ git add README.MD
$ git commit -m 'Test commit'
```
Change will not commit because one tests is error. 

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
