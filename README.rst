=========
pkgbuilds
=========
My PKGBUILDs for `Arch Linux`_ and `Arch Linux 32`_.

Git configuration
-----------------
Make sure to set the following options globally or on a per-repository basis,
**before** initializing the submodules:

.. code-block:: cfg

  [url "https://aur.archlinux.org/"]
    insteadOf = "aur:"
  [url "ssh+git://aur@aur.archlinux.org/"]
    pushInsteadOf = "aur:"

Categories
----------
* aur: Packages maintained on AUR_ (as git submodules).
* fixes: Fixes for non-uptodate packages, not maintained by me.
* local: Packages maintained for my own use, which do not warrant an upload to the AUR.


.. _AUR: https://aur.archlinux.org/
.. _Arch Linux 32: https://www.archlinux32.org/
.. _Arch Linux: https://www.archlinux.org/
