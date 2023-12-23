# awesome-custom-images

This list is an attempt to organize and collect public configs of people's custom OStree native containers.
This will help others build their own and allow for us to learn from each other.

- [Fedora CoreOS Examples Repository](https://github.com/miabbott/coreos-layering-examples) - a collection of examples to start with and derive from, start here!

> **Warning**
> This is still a relatively new feature, take precautions when testing on an installation you care about. :smile:

## Configs

(In alphabetical order)

- [Agus Lopez (aguslr)](https://github.com/aguslr)
     - [bluevanilla](https://github.com/aguslr/bluevanilla) - A custom Silverblue image that uses vanilla GNOME and FlatHub apps
     - [bluefusion](https://github.com/aguslr/bluefusion) - A custom image that adds RPM Fusion with media codecs and replaces Toolbox with Distrobox
- [Alessandro Di Stefano (aleskandro)](https://github.com/aleskandro/my-ostree-config) - OSTree-native container configs for a custom Fedora Kinoite for personal use
- [ayhc](https://github.com/ayhc/cerulean) - An opinionated Fedora Kinoite spin (customized for personal use)
- [Benjamin Sherman](https://github.com/bsherman)
  - [ublue-kmods](https://github.com/bsherman/ublue-kmods) - "Nearly vanilla" variant images with xbox controller akmods added; based on [ublue-os/nvidia](https://github.com/ublue-os/nvidia).
  - [ublue-custom](https://github.com/bsherman/ublue-custom) - Personalized variant images inspired by [ublue-os/base](https://github.com/ublue-os/base) but with system Flathub, per-variant packages, and script for TPM2 LUKS auto-unlock; based on *ublue-kmods*.
- [Dallas Strouse (Oro)](https://github.com/orowith2os/uBlue-Budgie) - A WIP rpm-ostree image based on uBlue, for Budgie
- [Jorge Castro](https://github.com/ublue-os) - Community built OS images based on Fedora Silverblue
  - [base](https://github.com/ublue-os/base) - A base image you can start from
  - [ubuntu](https://github.com/ublue-os/ubuntu) - Fedora Silverblue for Ubuntu Expatriates
- [Kyle Gospodnetich](https://github.com/KyleGospo)
  - [bazzite](https://github.com/ublue-os/bazzite) - Bazzite is an OCI based off of [kinoite-nvidia](https://github.com/ublue-os/nvidia) that is intended to be an alternative OS for the Steam Deck and a SteamOS-alike for desktops.
  - [serverblue](https://github.com/KyleGospo/serverblue) - Fedora CoreOS with cockpit, podman-docker, automatic updates via rpm-ostreed, and services for duperemove/distrobox-upgrade/flatpak updates.
- [Martin Pitt](https://github.com/martinpitt)'s [SwayWM](https://swaywm.org/) desktop OSTree
     - [minimal ostree build from scratch](https://github.com/martinpitt/ostree-pitti-workstation) (production)
     - [experimental CoreOS fork](https://github.com/martinpitt/pitti-workstation-oci) (much simpler, still some bugs)
- [Pavel Sobolev (paveloom)](https://github.com/paveloom-d/paveloom-os) - An OSTree native container for personal use
- [Secureblue](https://github.com/secureblue/secureblue) - A security optimized Distribution, limiting attack surface, and protecting from known and unknown risks, while staying user-friendly.
     - Desktops (Silverblue, Kinoite, Sericea, Bluefin, Lazurite) with user namespaces disabled, using bubblewrap-suid; or with user namespaces and bubblewrap
     - Server image with or without user namespaces
- [sihawken](https://github.com/sihawken/kinoite-msi-stealth-15m) - This is a build of kinoite specifically designed to support the MSI Stealth 15m
- [Yosuke Matsumura (GuiltyDoggy)](https://github.com/GuiltyDoggy/ostree-container) - Proof of concept for custom image for rpm-ostree container-native deployment

## Documentation and Specifications

- Spec: [OStree Native Containers](https://fedoraproject.org/wiki/Changes/OstreeNativeContainer): Important!
- Spec: [Ostree Native Container (Phase 2, stable)](https://fedoraproject.org/wiki/Changes/OstreeNativeContainerStable): Important!

## Discussions

- [Feature for custom rpm-ostree container-native builds?](https://discussion.fedoraproject.org/t/feature-for-custom-rpm-ostree-container-native-builds/44480)

## Video Content

- [Silverblue's move to bootable OCI images](https://www.youtube.com/watch?v=X8h304Jp9N8)
- [Image-based customization with Fedora Silverblue](https://www.youtube.com/watch?v=9xO4w-w8mzg)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

If you don't know how to use git then file an issue and leave a link, I'll integrate it into the list!
