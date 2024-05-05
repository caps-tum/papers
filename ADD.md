# Adding papers

This repository uses the [`git submodule`](https://git-scm.com/book/en/v2/Git-Tools-Submodules) feature. 
If you want to add a paper to this repository, please adhere to the following procedure:

1. Create a new repository with the name format `paper-<year>-<conference>-<shortname>` in the `caps-tum` group and populate it with your paper data & code.
2. Locally clone this repository (or pull changes if already done prior)
3. Run `git submodule add git@github.com:caps-tum/path-to-your-paper path-to-your-paper`
4. Update the README.md by adding your paper information to the table
5. Commit and push the changes to the `papers` repository
