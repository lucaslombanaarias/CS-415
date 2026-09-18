# CS 415 — Lucas Lombana Arias

Coursework for CS 415 (Game Development), UIUC.

## MP1 — Your First Game, An Infinite Matrix

A Matrix-themed infinite tunnel runner built in **Unreal Engine 5.6** (Blueprint-only).
Built on top of the Kodeco "How to Create a Simple Game in Unreal Engine 4" tutorial,
plus the additional features required by the MP1 spec.

**Project location:** `MP1/InfiniteMatrixStarter/InfiniteMatrix.uproject`

### Required features
- [ ] Tutorial complete (infinite tunnel spawning, mouse steering, obstacle walls, restart button)
- [ ] Health system (HUD bar, damage on wall overlap, pass-through, max health, resets on restart)
- [ ] Score (HUD counter, increments only on a clean pass through the hole, resets on restart)
- [ ] Health packs (randomized spawn, max once per tunnel, heals up to max, despawns)
- [ ] Player projectile attacks (left click, outruns the player, despawns on hit/timeout)
- [ ] Enemies (collidable, killable by projectile for score, damages player on contact)
- [ ] Player speed increase over time (resets on restart)
- [ ] Two creative modifications

### Creative modifications
1. _TBD_
2. _TBD_

## Working with this repo

Unreal binary assets (`.uasset`, `.umap`) are stored via **Git LFS**. After cloning:

```bash
git lfs install
git lfs pull
```

Without git-lfs installed, asset files will appear as small text pointer files and the
project will not open correctly.
