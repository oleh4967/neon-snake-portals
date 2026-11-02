## Neon Snake: Portals — first public release

A neon Snake arcade with paired portals, five arenas, gamepad support, and a portable Windows release. Built with Python and Pygame.


A neon-styled Snake arcade with five handcrafted arenas and paired portals.
Collect energy, plan your exits, and keep your growing snake out of trouble.

### Download and play

Download **NeonSnakePortals-1.0.0-Windows-x64.zip** from the assets below.
Extract the entire archive, then double-click **NeonSnakePortals.exe**.
**No Python installation is required.**

Keep the `_internal` folder beside the EXE. For a desktop icon, run
`CreateDesktopShortcut.cmd` after moving the game to its final folder.
GitHub's automatic **Source code** downloads are for developers, not the
ready-to-play Windows application.

### Included

- Five arenas with progressive speed and obstacle layouts.
- Portal pairs A/B, preserved exit direction, and unsafe-exit previews.
- Ordinary energy spheres and timed golden bonuses.
- Keyboard, mouse menus, SDL gamepad support, and fallback control assignment.
- Neon visuals, synthesized sound, and reduced-effects settings.
- Saved records, unlocked arenas, and configurable controls.

### Controls

- **Arrow keys / WASD:** steer and navigate menus.
- **Enter:** confirm and start.
- **Space / P:** pause or resume.
- **Escape:** back or pause during play.
- **R:** retry after defeat.
- **Gamepad:** D-pad / left stick, A / B / X / Start.

### Platform and verification

Windows x64 build, targeting Windows 10/11 and tested on Windows 11.
The build is unsigned. Other computers, Windows 10, and physical controller
hardware have not yet been verified. Native macOS/Linux/ARM builds are not included.

All **53 source tests passed**, including a full seeded campaign. The portable
EXE passed relocation, startup, rendering, unavailable-audio, save-reload, and
desktop-shortcut checks on the build machine with external Python paths cleared.

**SHA256SUMS.txt** contains the checksum for the portable ZIP.
Original game sources, dependency notices, and licenses are included in the
download. Please report reproducible problems through this repository's Issues.
