# packages
This repository contains the customizations to packages needed to port them to i686 and/or our environment, as well as other package related informations.

* There are subdirectories `repository/package` which contain new packages and customizations for existent packages to compile for i686 or adopt to our environment.
In case, the files therein exist in the respective original package, the respective original package files are either appended (in case of `PKGBUILD`) or overwritten (for other files).
* The file `blacklist` containes a list of packages which won't be built for i686 (because they can't be built for or are useless on i686).
* The file `extra-from-multilib` contains a list of packages which are in multilib for x86_64, but belong in extra (and not community) for i686.
