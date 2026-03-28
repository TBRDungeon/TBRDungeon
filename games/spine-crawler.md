---
layout: game
title: Spine Crawler
tagline: "The dungeon remembers every book you've forgotten."
accent_color: "#00FF41"
bg_color: "#0a0a1a"
youtube_id: YOUR_VIDEO_ID
banner: spine-crawler.png
screenshots:
  - spine-crawler/title.png
  - spine-crawler/entrance.png
  - spine-crawler/library.png
  - spine-crawler/combat.png
  - spine-crawler/map.png
mac_download_url: "#"
windows_download_url: "#"
---

You stand at the mouth of a dungeon that shouldn't exist. The air smells of old paper and torchlight. A terminal flickers to life at your feet, its phosphor-green cursor blinking patiently. You type GO NORTH. The dungeon answers. Welcome to Spine Crawler, where every room you explore and every monster you survive brings you closer to a reading list forged in the dark.

## The Premise

Spine Crawler is a text adventure TBR game inspired by 1980s classics like The Pawn, Magnetic Scrolls, and early King's Quest. The screen splits into two zones: pixel-art scene backgrounds fill the top two-thirds, while a retro green-on-black command terminal occupies the bottom. You explore a procedurally generated library-dungeon by typing commands, discovering book prompts through combat, puzzles, traps, and treasure to build your TBR reading list.

> "A spectral librarian whispers: 'You seem to be missing something...' A book appears at your feet."

Choose your path through three doors. Fight dust wraiths and ink elementals. Solve literary riddles. Dodge book worms that devour your reading list. Every encounter is a chance to add a real book to your shelf — if you survive long enough to reach the exit.

## How It Works

- **3 difficulty levels** — The Quick Read (5 books, ~15 min), The Shelf (8 books, ~20 min), The Hoard (12 books, ~30 min)
- **10 room types** — corridors, chambers, libraries, trap rooms, treasure vaults, NPC alcoves, puzzle chambers, boss rooms, and more
- **Text parser with 60+ synonyms** — type natural commands like GO NORTH, LOOK, TAKE SWORD, ATTACK, FLEE, USE POTION
- **6 enemies + 2 bosses** — Dust Wraiths, Shelf Mimics, Page Phantoms, Ink Elementals, and bosses like The Librarian and The Curator
- **10 literary riddles** — solve book-themed puzzles to earn bonus prompts and rare items
- **125 book prompts** — across genre, theme, mood, challenge, and wild categories
- **15 items** — healing potions, rusty swords, bookmark shields, compasses, reading lamps, and more
- **Seeded dungeons** — same seed generates the same dungeon, so you can share runs with friends

## Features

- **Classic text adventure feel** — command-line interface with retro phosphor-green terminal aesthetic
- **Visual map overlay** — type MAP to see a graphical dungeon map with fog-of-war, room type colors, and a pulsing beacon on your position
- **Hint system** — type HINT for atmospheric, contextual clues that guide without spoiling
- **Procedural audio** — 13 synthesized sounds including footsteps, combat hits, book discovery chimes, and a victory fanfare, all generated with Web Audio
- **Midjourney pixel-art backgrounds** — 11 hand-crafted scenes bring the dungeon to life
- **Save and load** — pick up where you left off with persistent game state
- **Game history** — browse past adventures and the reading lists they produced
- **Cross-game TBR sync** — your reading lists sync across all TBR Games via the Shared TBR Library
- **Desktop app** — available for Mac and Windows via Tauri
