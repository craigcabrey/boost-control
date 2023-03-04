# `boost-control`

Turn boost ("turbo" for Intel systems) on and off as the power profile changes. Listens for D-Bus messages from `power-profiles-daemon`. Without it, nothing happens.

## Install

1. Copy each file to its counterpart on your OS install root.
2. Run `systemctl daemon-reload`
3. Run `systemctl enable --now boost-control`
4. Run `udevadm control --reload` (alternatively, reboot)

Someday I'll package this up more correctly.
