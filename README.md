# SCID

___A chess database application___

SCID (Shane's Chess Information Database) is a chess database application that allows users to store, organize, and search through large collections of chess games. It also includes chess engines for playing against the computer and analyzing positions. Any Xboard or UCI compatible engine is supported. 

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub io.github.benini.scid
flatpak run io.github.benini.scid
```

## Building

```bash
git clone git@github.com:flathub/io.github.benini.scid.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.github.benini.scid.yml
```
