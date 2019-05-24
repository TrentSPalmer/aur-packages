### Where are we Dorothy?
Stash of Arch Linux PKGBUILDS, some of which are forks, some of which are inspired,
and also some which are updates to outdated AUR packages.

Additionally, I have some PKGBUILDS here merely so I can track their updates
with my own scripts.

### Live Git PKGBUILD tip
If you want to modify a PKGBUILDS to pull a particular commit, you can edit
the source like so.

```conf
# source=("${_name}::${url//https/git}")
source=("${_name}::${url//https/git}#commit=<commit_hash>")
```
