# VIA Keymaps

These are keymaps for keyboards configured using VIA.

Most modifications allow for a rough approximation of vi movement through the keyboard.

## Notes
* Layer shift:
  * Set key to ANY
  * LT(4,KC_SCLN)

## VIA Setup
* NixOS
  * Setup udev rules in system configuration.nix:
    * `services.udev.packages = with pkgs; [ via ];`
  * Install and run `via`
* Other
  * Use Chrome to visit https://usevia.app/
  * `chmod a+rw /dev/hidraw*`
