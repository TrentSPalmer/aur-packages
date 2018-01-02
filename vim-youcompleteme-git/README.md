### Fork Information

pull in https://aur.archlinux.org/vim-youcompleteme-git.git at commit
287e486c299ea35c95fe8dd1e854dba9cdbaeb35;
all previous maintainers and contributors will be listed as
contributors

### Build Options

extends the build options: `_omnisharp`, `_gocode`, `_rust`, and `_tern`
throughout the PKGBUILD, in order to avoid unneeded git clones/pulls
and dependancy installs

### RaspberryPi (armv7h)
doesn't build with option `_omnisharp=y`, and takes forever to build with
`_rust=y`
