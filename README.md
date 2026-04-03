# Hurricane (GZ Fork)

Fork of [Hurricane](https://github.com/GeyserMC/Hurricane) with Minecraft 26.1 support.

## Changes from upstream

- Fixed NMS version detection for modern Paper (unversioned CraftBukkit packages)
- Added mojmap class name support (`BambooStalkBlock`, `Shapes`) for 26.1+
- Fixed bamboo collision field lookup using mojmap field name `SHAPE_COLLISION`
- Added `Shapes.box()` method fallback for mojmap servers

## Original Description

Various workarounds for Geyser players that modify the server in order to achieve their goal.

Issues with each workaround are listed in the plugin's config. **Please take your time to read them as the workarounds in this plugin can be used for exploitative purposes.**

## Fixes:
- Bamboo and dripstone collision (by setting them to no server-side collision)

Supported Versions:
- 1.14.x - 26.1+
