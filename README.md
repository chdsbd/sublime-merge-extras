# sublime-merge-extras

Extra commands for Sublime Merge

## usage

### `Checkout Previous Branch`

Checks out last reference with `git checkout -`.

### `Switch to Previous Branch`

Checks out last reference with `git checkout -`.

### `Merge Previous Branch`

Merge in last reference with `git merge -`.

### `Create Empty Commit`

Creates an empty commit with `git commit --allow-empty -m "empty commit"`. This is helpful for retriggering CI.

### `Undo`

Undoes the last action via `git undo` from https://github.com/tj/git-extras.

### `Open Pull Request`

Opens pull request for current branch on GitHub via `git pr`. Works well with [`git-pr` from NPM](https://www.npmjs.com/package/git-pr).

### `Checkout Pull Request Locally`

Open GitHub pull request locally via `git gh pr checkout $text`. [Install the GitHub CLI](https://cli.github.com) and add an alias via `git config --global alias.gh '!gh'`.

## installation

### system link (recommended)

```
git clone https://github.com/chdsbd/sublime-merge-extras.git
cd sublime-merge-extras
ln -f ./SublimeMergeExtras.sublime-commands ~/Library/Application\ Support/Sublime\ Merge/Packages/User/SublimeMergeExtras.sublime-commands
```

### copy, paste

Place `SublimeMergeExtras.sublime-commands` in `~/Library/Application Support/Sublime Merge/Packages/User/`.
