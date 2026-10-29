# NIRUX Theme: Hackerman Oldschool

A NIRUX suite theme pack.

- Theme ID: `niru-hackerman-oldschool`
- Display name: **Niru Hackerman Oldschool**
- Background: `#07100a`
- Foreground: `#b8d8b5`
- Muted: `#6f8f70`
- Border: `#1c3522`
- Focus: `#39d353`
- Wallpaper: `nirux-wallpaper-hackerman-oldschool-4k.png` (3840×2160)

## Install

NIRUX must be installed and `niructl` must be in `PATH`.

```sh
./install.sh
niructl theme niru-hackerman-oldschool
```

The installer uses `niructl theme-import`, so it validates the theme and
installs both the palette and wallpaper into the standard per-user locations.
No root access is required.

To replace an existing installation after a pack update:

```sh
./install.sh --replace
niructl theme niru-hackerman-oldschool
```

## Uninstall

```sh
./uninstall.sh
```

## Compatibility

The theme is a user theme, so the suite discovers it without being added to any
built-in theme list. Components that follow the shared NIRUX theme pick it up:
NIRUWM, NIRUBAR, NIRU Launcher, NIRUNOTIFY, NIRULOCK, NIRUSCREENSAVER,
NIRUSHOT, NIRUPRES editor chrome, NIRUFLOW, NIRUORG and NIRUNOTE with
**Follow NIRUX**. NIRUPRES slide themes remain independent by design.
