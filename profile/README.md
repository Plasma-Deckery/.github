# Plasma Deckery

Using a Steam Deck as an actual computer means fighting the parts of a Linux
desktop that assume a keyboard. These projects remove those assumptions one at
a time.

## Deckery — input

The Steam Deck is a capable handheld computer, but in desktop mode it is
awkward to use without a physical keyboard. The mouse gets you some of the way;
real desktop efficiency runs on shortcuts, and those are not available when you
are away from a desk.

Deckery remaps controller buttons to keyboard keys, shortcuts and actions —
with per-app layouts, modifier layers, and a live overlay that shows exactly
what every button does at any given moment. The goal is full desktop
productivity with just the controller in hand, and independence from Steam:
every button, trigger and trackpad usable without the Steam process running in
the background. It also ships opinionated KDE Plasma 6 configuration that
adapts the desktop to handheld use.

- **[deckery](../../../deckery)** — the input stack, configuration and docs
- **[deckery-hud](../../../deckery-hud)** — the live overlay showing what the
  controller currently does
- **[makima-deckery](../../../makima-deckery)**, **[evdev](../../../evdev)** —
  forks of the input layers underneath

## Deckery Auth — authentication *(beta)*

Typing a sudo password on a handheld is miserable. This authenticates you with
the controller instead: a PAM module, an auth daemon and an input reader,
covering sudo, polkit and the lock screen without a keyboard.

- **[deckery-auth](../../../deckery-auth)**

## Tools

Smaller KDE and Steam Deck pieces that do not need a project of their own.

- **[deckery-spatnav](../../../deckery-spatnav)** *(alpha)* — spatial navigation
  overlay for KDE Plasma, so a stick can move between on-screen elements
- **[tinkergame](../../../tinkergame)** — fork of the Steam game-launch wrapper,
  with automatic Non-Steam artwork
- **[kyanite](../../../kyanite)** — dynamic workspaces for Plasma 6
- **[maximized-window-gaps](../../../maximized-window-gaps)** — spacing around
  maximized windows
