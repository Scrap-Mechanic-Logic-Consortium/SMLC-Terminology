---
title: Ice Cream Index
description: A set of terminology used to describe the extent to which a creation uses mods.
---

# Icecream Index

The Ice Cream Index is a set of terminology used to describe the extent to which a creation uses mods.

- **Vanilla** = No mods are used.
    - **Strict/Glitchless Vanilla** = Absolutely no mods, BP edits, glitches, self-wires, or non-vanilla colors are allowed in this category.
    - **Spawnable vanilla** = BP editing, self wires, glitch welds, and non-vanilla colors are allowed. Creations that are too big to spawn on the lift in vanilla, do not qualify for this category.
- **Modded** = Requires *any* mods to spawn/use
    - **Light modded** = Uses only mods that exclusively implement boolean alternatives to vanilla logic (limited to the boolean operators AND, OR, XOR, and their inverted counterparts). Mods that internally optimize the logic are allowed. It does not matter what the mod does internally as long as the outcome of the circuit is the same.
        - **Theoretical vanilla** = Uses mods that implement boolean logic gates to reduce gate count or lag without a per tick performance gain. One-block memory is allowed as an exception as long as it could be replaced by vanilla logic with the same behavior (connection limit, delay, and throughput).
        - **Logic tweaks** = Identical to theoretical, but the connection limit is ignored or a logic speedup mod is required for it to work at all because it needs to keep up with SM physics, and/or it needs to be faster than the rest of the vanilla logic system. (think self-driving cars, rolling-window screens, ect…)
    - **Auxiliary modded** = Uses mods for physics-based improvements, decoration, etc.. (eg modded pistons)
    - **Alternative logic modded** = Uses mods that implement mathematical function blocks / computers.
        - **Mathematical** = Uses modded gates and blocks that are not intrinsically turing-complete (ie modpack number logic like blocks).
        - **Block Computer** = Uses modded parts that are intrinsically turing-complete (ie can run any program that a computer can run in a block).
