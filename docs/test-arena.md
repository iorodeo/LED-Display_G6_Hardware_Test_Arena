---
title: Test Arena
parent: Generation 6
nav_order: 2
---

1. TOC
{:toc}

# Test Arena

The Generation 6 test arena is a small hardware project associated with the G6 arena. It was intended as a development platform for arena firmware, but it was never actually used.

This page is therefore intentionally short. The main value of this repository section is as a record of the design files, production outputs, and the small amount of build history that is still known.

## What it is

The local `README.mdown` describes this folder as containing the KiCad design and production files for the **G6 panel test arena hardware**.

In practical terms, this board appears to have been a development-only test platform rather than part of the final Generation 6 arena hardware path. It was meant to support firmware work for the arena before moving to the full system.

## Known build history

The known production history is:

- **Will Dickson v1.1**
- **Will Dickson v1.2**
- **Janelia v1.1**

Although the project was built in multiple revisions, it was never actually used. For that reason, this hardware should be treated as historical development material rather than as a recommended build for new systems.

## Files in the repository

The main project folders are:

- `test_arena_v1r1/`
- `test_arena_v1r2/`

These folders contain the editable KiCad source files for the test arena, including schematic, PCB, and project files.

Both revision folders also contain production outputs such as:

- `test_arena.zip`
- `bom.csv`
- `positions.csv`
- `designators.csv`
- `netlist.ipc`

Archived manufacturing outputs are kept under:

- `test_arena_v1r1/production_archive/`
- `test_arena_v1r2/production_archive/`

The top-level `Generation 6/Hardware/` folder also includes rendered images of the board in `images/`.

## Current status

This hardware is best understood as an unused firmware-development branch of the Generation 6 arena project.

If you need to inspect its history, start with:

- `Generation 6/Hardware/test_arena_v1r1/`
- `Generation 6/Hardware/test_arena_v1r2/`
- `Generation 6/Hardware/README.mdown`

For new work on Generation 6 arena hardware, this test arena should not be the default starting point. Instead have a look a the [G6 Arena]({{site.baseurl}}/Generation 6/Arena/docs/arena.html)
