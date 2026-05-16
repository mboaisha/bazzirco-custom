# Bazzirco-Custom
- Use `bazzirco-nvidia` as base image and add personal tweaks
  - `bazzirco` is an attempt to combine [Bazzite](https://github.com/ublue-os/bazzite) and [Zirconium](https://github.com/zirconium-dev/zirconium) 
- Instead of using `bazzirco-dx-nvidia`, you could use `bazzirco-nvidia` as a base image then use Bluebuild to roll your own "DX" tooling.
- Experimental and highly personalized. Might add couple of things to suit my pre-built PC that has a terrible motherboard.
  - Will release a more "generic" or "general use" image at some point.

## What does this image have?
- DX Tooling
  - Virtualization (`libvirt`, `virt-manager`, et al)
  - VSCodium instead of VSCode
  - `neovim` preinstalled
  - Helpful flatpaks such as Podman Desktop
