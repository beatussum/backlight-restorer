# save-backlight

This script is an **OpenRC** service aiming to restore the last brightness level on reboot. It is a fork of the [antipatico's project](https://github.com/antipatico/backlight-openrc).

## Installation

### On Gentoo-based distributions

1. Add the [beatussum-overlay](https://github.com/beatussum/beatussum-overlay).
2. emerge the _sys-apps/save-backlight_ package.
3. Add service to the _default_ runlevel:
```bash
rc-update add save-backlight default
```

### On others distribution

Just use `make install` and `make uninstall`.
