# Fog Naval Console

A browser-based ship-to-ship combat tracker built for **The Land of Fog**, a tabletop campaign I run. It manages naval battles on a grid — ship movement, heading, initiative order, and round tracking — so combat stays fast and visual at the table.

**Live app:** https://wyatt-skaar.github.io/fog-naval-console/

## What it does

- Add friendly and hostile ships by hull type (Sloop, Schooner, Brigantine, Galleon, Manowar, or a custom hull)
- Drag ships around the grid to move them, and drag a heading handle to turn them
- Track turn order automatically by initiative
- Configure the grid (columns, rows, feet per square) and zoom to match any battle map
- Toggle move range and distance overlays to adjudicate combat at a glance
- Save and reload ship templates and full battle setups

## About this project

I designed the naval combat system and rules used in my campaign, and I directed Claude (Anthropic's AI) to build this tool to run it at the table. I'm not a programmer — my role was designing the mechanics, specifying how the tool should work, and testing it extensively through real play sessions to refine it.

## V2

This is the current version. It adds:

- A **move mode** toggle, to separate positioning ships from moving them during combat
- The ability to **add and remove extra systems and weapons** on a ship, beyond its base hull loadout

## Running it locally

This is a single self-contained HTML file. Download `index.html` and open it in any modern browser — no install or server required.
