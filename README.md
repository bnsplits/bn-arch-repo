# Bn Arch Repository

A personal Arch Linux repository maintained by **BnSplit** (AKA me).

---

## Repository Setup

To use this repository, add the following lines to your `/etc/pacman.conf`:

```ini
[bn-arch-repo]
SigLevel = Optional TrustAll
Server = https://bnsplits.github.io/bn-arch-repo/x86_64
```

Then update the package databases:

```bash
sudo pacman -Sy
```

You can now install packages directly from this repository using `pacman`.

---

## Packages

- [bnclip](https://github.com/bnsplits/bnclip)
- [chromafade](https://github.com/bnsplits/chromafade)
- [chromapick](https://github.com/bnsplits/chromapick)
- [hypr-go-to-workspace](https://github.com/bnsplits/hypr-go-to-workspace)
- [hypr-move-to-workspace](https://github.com/bnsplits/hypr-move-to-workspace)
- [anime-dive](https://github.com/bnsplits/anime-dive)
- [mpv-bn](https://github.com/bnsplits/mpv-bn)
- [n-m3u8dl-re-bin-bn](https://github.com/nilaoda/N_m3u8DL-RE)

---

## Notes

- All packages are built from source and may contain small adjustments for personal workflows.
- This repository is intended for personal or experimental use. Use at your own discretion.

---

**Maintainer:** [BnSplit](https://github.com/bnsplits)

**License:** Same as the upstream projects unless otherwise stated.
