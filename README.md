# pkgbuilds
My PKGBUILDs for [Arch Linux][1].

## Git configuration
Make sure to set the following options globally or on a per-repository basis,
before initializing the submodules:

```INI
  [url "https://aur.archlinux.org/"]
    insteadOf = "aur:"
  [url "ssh://aur@aur.archlinux.org/"]
    insteadOf = "aur:"
```

## Categories
* aur: Packages maintained on [AUR][2] (as git submodules).
* fixes: Fixes for non-uptodate packages, not maintained by me.
* local: Packages maintained for my own use, which do not warrant an upload to the AUR.

[1]: https://www.archlinux.org/
[2]: https://aur.archlinux.org/
