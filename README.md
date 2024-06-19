# Endre
Automatic changelog generator

Features:

* Generates a CHANGELOG.md file based on git log
* Can generate a global CHANGELOG.md based on all sub-repos in multi-repo

All git commit messages must be prefixed with:

* feat
* fix
* docs
* style
* refactor
* perf
* test
* chore

References to issues will be automatically linked if they start with \#n, where _n_ is the issue number of the /issues for the repository URL found in package.json.
