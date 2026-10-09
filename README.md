# Island Media Controls - Fork

A fork of [Island Media Controls](https://github.com/usho-lear/island-media-controls)
by usho (MIT). It puts the current media session into the Windows 11 taskbar as
a compact island with artwork, title, artist and progress. Playback buttons
slide out next to the island, and a click opens a larger player with seek bar
and controls.

## What this fork adds

- **Taskbar choice:** attach the island to the main taskbar, the second
  monitor's taskbar, or the second one only.
- **Placement:** next to the tray (far left/right, around the clock), as an
  overlay on the taskbar (left/center/right), or pinned to the **screen edge**
  (left/right). The screen-edge options also work with styled or split taskbars
  (for example the WindowGlass theme of Windows 11 Taskbar Styler).
- **Configurable buttons:** choose which of previous, play/pause, next,
  shuffle and repeat are shown and in what order. Buttons a source does not
  support (for example shuffle/repeat in a browser) are hidden automatically.
- **Apple Music support:** shuffle, repeat and seek work through a small bridge
  loaded into `AppleMusic.exe`, so the Apple Music window is not brought up.
  Restart Apple Music after installing or updating the mod.
- **Side buttons and big player are separate:** side buttons can appear on
  hover, always, or never; the big player can be full, compact, or disabled.
  The island stays visible while the big player is open and the two share one
  outline and palette.
- **Several media sources:** scroll the mouse wheel over the island or the big
  player to switch between sources (e.g. Apple Music and YouTube). The old
  source can be paused and the new one started automatically, and the island
  can follow the source that starts playing. Dots show how many sources there
  are.
- **Six button styles** shared by the side buttons and the big player.
- **Autohide-friendly:** with an auto-hiding taskbar, clicking the island
  buttons does not leave the taskbar stuck open.
- **Close the big player when the cursor leaves it** (after a click inside it).
- Russian settings translation.

## Notes

- With glass and transparent materials the big player blurs the screen behind
  it using Windows Graphics Capture. It is hidden from screenshots and screen
  sharing by default; enable the capturable backdrop option if it must appear
  in captures.
- For the second monitor, enable "Show my taskbar on all displays" in Windows.

## Credits

Original mod and design: usho
([island-media-controls](https://github.com/usho-lear/island-media-controls),
MIT License).
