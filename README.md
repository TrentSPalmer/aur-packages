### Where are we Dorothy?
my own Arch Linux PKGBUILDS, some of which are forks, and some of which are inspired

### Live Git PKGBUILD tip
If you want to modify a PKGBUILDS to pull a particular commit, you can edit
the source like so.

```conf
# source=("${_name}::${url//https/git}")
source=("${_name}::${url//https/git}#commit=<commit_hash>")
```
