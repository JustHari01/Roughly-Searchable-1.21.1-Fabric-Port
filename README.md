# Roughly Searchable (UNOFFICIAL) — Fabric 1.21.1

An unofficial Minecraft 1.21.1 Fabric compatibility port of [Roughly Searchable](https://modrinth.com/mod/roughly-searchable) by Stuin. The original source is available at [stuin/RoughlySearchable](https://github.com/stuin/RoughlySearchable); this port is based on upstream commit `c229e2e9293ce2b8005b33dfb08e8b847f02b7ab`.

## Features

- Highlights items in an inventory when they match the active Roughly Enough Items search.
- Lets you configure the scale of matching and non-matching items.
- Provides a configurable keybind to toggle the search behavior.
- Can synchronize the REI search-field highlighting with this mod's search toggle.

## Requirements

- Minecraft 1.21.1
- Java 21 or newer
- Fabric Loader 0.15.11 or newer
- Fabric API for Minecraft 1.21.1
- Roughly Enough Items for Fabric 1.21.1, version 16.0.799 or newer
- Cloth Config for Fabric 1.21.1, version 15.0.130 or newer

This is a client-side mod and should not be installed on a dedicated server.
Minecraft client runtime testing for 1.21.1 has not yet been performed.

## Build

Run `gradlew remapJar` with Java 21. The output is written to `build/libs/`.

## Attribution and license

This port retains the upstream MIT license and copyright notice. The original mod is by Stuin; this repository contains the Minecraft 1.21.1 compatibility changes and release metadata for the unofficial port. See [LICENSE](LICENSE).

AI assistance was used for the compatibility port and release documentation; the original mod and its source remain attributed to Stuin.
