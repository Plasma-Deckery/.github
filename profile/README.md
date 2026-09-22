# Plasma Deckery

Using a Steam Deck as an actual computer means fighting the parts of a Linux
desktop that assume a keyboard. These projects remove those assumptions one at
a time.

## Deckery — input

An input remapper that knows what you are doing. It is aware of the focused
application and of the desktop environment, so the same button means different
things in different places. The point is not to memorise keyboard shortcuts —
it is to stop needing them, by mapping the controller directly to shortcuts,
commands and actions.

- **[deckery](../../../deckery)** — the context-aware input stack
- **[deckery-spatnav](../../../deckery-spatnav)** — spatial navigation overlay
  for KDE Plasma, so a stick can move between on-screen elements
- **[deckery-hud](../../../deckery-hud)** — transparent overlay showing what
  the controller currently does
- **[makima-deckery](../../../makima-deckery)**, **[evdev](../../../evdev)** —
  forks of the input layers underneath

## Deckery Auth — authentication *(beta)*

Typing a sudo password on a handheld is miserable. This authenticates you with
the controller instead: a PAM module, an auth daemon and an input reader,
covering sudo, polkit and the lock screen without a keyboard.

- **[deckery-auth](../../../deckery-auth)**

## Tools

Smaller KDE and Steam Deck pieces that do not need a project of their own.

- **[tinkergame](../../../tinkergame)** — fork of the Steam game-launch wrapper,
  with automatic Non-Steam artwork
- **[kyanite](../../../kyanite)** — dynamic workspaces for Plasma 6
- **[maximized-window-gaps](../../../maximized-window-gaps)** — spacing around
  maximized windows
