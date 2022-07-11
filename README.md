# sublime-merge-extras
Extra commands for Sublime Merge

## usage

### `Create Empty Commit`

Creates an empty commit that is helpful for retriggering CI.

### `Checkout Last`

Checks out last reference with `git checkout -` .

### `Undo`

Undoes the last action via git-undo from https://github.com/tj/git-extras.

### `GitHub: Open Pull Request`

Opens pull request for current branch on GitHub.

## installation

### copy, paste

Place `SublimeMergeExtras.sublime-commands` in `~/Library/Application Support/Sublime Merge/Packages/User/`.

### system link

```
git clone https://github.com/chdsbd/sublime-merge-extras.git
cd sublime-merge-extras
ln -f ./SublimeMergeExtras.sublime-commands ~/Library/Application\ Support/Sublime\ Merge/Packages/User/SublimeMergeExtras.sublime-commands   
```