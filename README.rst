=========
pkgbuilds
=========
My PKGBUILDs for `Arch Linux <https://www.archlinux.org/>`_.

Git configuration
-----------------
Make sure to set the following options globally or on a per-repository basis,
before initializing the submodules:

.. code-block:: cfg

  [url "https://aur.archlinux.org/"]
    insteadOf = "aur:"
  [url "ssh://aur@aur.archlinux.org/"]
    insteadOf = "aur:"

Categories
----------
* aur: Packages maintained on `AUR <https://aur.archlinux.org/>`_ (git submodules)
* fixes: Fixes for non-uptodate packages, not maintained by me
* local: Packages maintained for my own use, which do not warrant an upload to the AUR.
