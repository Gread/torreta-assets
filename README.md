# Torreta public assets

Public hosting for Torreta's Steam inventory images and authorized marketing
media (Steam app **2998660**). Game source and player data are not included.

## Campaign videos

[Open the campaign library](https://gread.github.io/torreta-assets/marketing/2026-10-21/)
for six 15-second concepts, each delivered for X (1920x1080) and Instagram
Reels (1080x1920). The page provides previews, direct MP4 downloads, suggested
captions and a JSON manifest with SHA-256 hashes. All downloads work without
authentication or access to the game's private repository.

The complete ZIP is attached to the public `campaign-2026-10-21` release and
linked from the gallery. Individual media and the manifest are served directly
by GitHub Pages. Existing inventory URLs remain unchanged.

## Steam inventory images

Steam inventory item definitions require externally hosted HTTPS `icon_url`
images. `crystals/` contains the Tower Crystal in five rarities: common,
uncommon, rare, epic and legendary. The generic `crystal_<rarity>.png` images
are 200x200; `_large.png` images are 2048x2048. `crystals/towers/` contains the
tower-specific variants.

The rarities share one crystal shape, with different color and internal glow.
They were baked from the game's procedural raymarching shader rather than
drawn as flat polygons.

## Rights

Copyright Ricardson Albuquerque. All rights reserved. Inventory images are
published to serve Steam item definitions; campaign assets are supplied for
authorized Torreta marketing. Public download availability does not grant a
general license to reuse the assets in other products.
