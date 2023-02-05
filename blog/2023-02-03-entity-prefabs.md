---
slug: entity-prefabs
title: Entity Prefabs - First Iteration
authors: garry_newman
tags: [development, discord]
---

Instead of spawning a raw entity in code and filling its attributes, adding components and children. we can have a "description" of an entity configuration to spawn. This can be copied, edited and updated outside of the game. This is an entity prefab.

This is the first iteration so I can find out what sucks nice and early. It should be safe enough to use right now and if the format changes I'll add upgraders so it'll retain backwards

https://github.com/orgs/sboxgame/discussions/2857