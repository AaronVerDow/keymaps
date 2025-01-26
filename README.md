# VIA Keymaps

These are keymaps for keyboards configured using VIA.

Most modifications allow for a rough approximation of vi movement through the keyboard.  See [my kanata configs](https://github.com/AaronVerDow/nix/blob/main/common/kanata/) for a software equivilent.  Kanata supports caps word and more layers; I would recommend that for anyone starting fresh.

## Notes
* Layer shift:
  * Set key to ANY
  * LT(4,KC_SCLN)

## VIA Setup
* NixOS
  * Setup udev rules in system configuration.nix:
    * `services.udev.packages = with pkgs; [ via ];`
    * `hardware.keyboard.qmk.enable = true;`
    * Keychron may need custom rules
  * Install and run `via`
* Other
  * Use Chrome to visit https://usevia.app/
  * `chmod a+rw /dev/hidraw*`

# Bluetooth Assignments

* Q2 Max (fn1)
  * 2.4Ghz: Living Room
  * Q: IdeaPad
  * W:
  * E:
* K9 Pro (fn)
  * Q: IdeaPad
  * W: Go Nix
  * E:
