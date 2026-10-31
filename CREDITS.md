# Credits

This repository is a copy of [Sandiep/openwrt](https://github.com/Sandiep/openwrt),
kept for personal builds for the JioRouter AX6000 (JIDU6J11). I did not write the
device support in it. All credit goes to the people below.

## Device support

- **Sandeep Sondagar ([@Sandiep](https://github.com/Sandiep))**: JIDU6J11 device support
  for the `qualcommbe/ipq95xx` target. This includes the device tree, IPQ9574 ath11k and
  mac80211 patches, the PSGMII phylink fix, board data and firmware packaging, and the
  build pipeline in [OpenWRT-JIDU6x11-Builds](https://github.com/Sandiep/OpenWRT-JIDU6x11-Builds).
  The work is on the `JIDU6J11-PR`, `JIDU6J11` and `qualcommbe-*` branches.
- **Mayank ([@themayankraut](https://github.com/themayankraut))**: the SSH flashing
  method (no UART needed), flashing scripts and documentation in
  [Jio-AX6000-6J11-OpenWRT-SSH](https://github.com/themayankraut/Jio-AX6000-6J11-OpenWRT-SSH).

## Upstream

- **[The OpenWrt Project](https://openwrt.org/)** and all its contributors. The original
  author of every commit is kept in the git history.
- The Linux kernel, Qualcomm IPQ95xx and ath11k contributors, for upstream hardware support.

## What this copy adds

- [@devprateekagrawal](https://github.com/devprateekagrawal) maintains this copy to build
  images with extra packages, such as Jool for NAT64/CLAT. Any changes made here are kept
  on separate branches, so the original branches stay as Sandiep published them.

## License

OpenWrt is licensed under GPL-2.0 (see `COPYING` and `LICENSES/`). If an image built from
this tree is shared, its source must be shared too.
