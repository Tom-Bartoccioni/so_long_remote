# so_long

> School project (42 / Epitech curriculum) — C

A small **2D tile-based game** built with the MiniLibX graphics library. The player moves across a map, collects every item, and reaches the exit — while a parser validates that the map is well-formed.

## Features

- Map loaded from a `.ber` file and validated (walls, reachability, required elements)
- Player movement with sprites and smooth display
- Collectibles and an exit
- Enemies (bonus)
- Clean exit and memory management

## Tech stack

- **Language:** C
- **Graphics:** MiniLibX
- **Build:** `Makefile`

## Build

```sh
make
./so_long map.ber
```

## What I learned

- 2D rendering and event handling with MiniLibX
- Map parsing and validation (flood-fill reachability)
- Sprite management and clean resource handling in C
