## PKGBUILDs for Arch Linux

Each PKGBUILD is stored as a git subtree. This makes it possible to have all
PKGBUILDs in one repository while synchronizing them independently with the AUR.

To add a PKGBUILD from an existing reposity (AUR >= 4):

        git subtree add -P ${name} ssh://aur@aur.archlinux.org/${name}.git master

        Use `push.sh` to push to the AUR.

        See `import.sh` for a helper script that will upload AUR4 PKGBUILD from AUR3 and
        save the corresponding subtree here.

-- thanks to https://raw.githubusercontent.com/Ambrevar/archlinux-pkgbuilds/master/ who will probably never know, but these 4 files cleared up the last git related confusion i had.
        