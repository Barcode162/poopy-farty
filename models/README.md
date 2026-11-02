# Blender models

Export from Blender as **glTF Binary (.glb)** and drop them here with these exact names:

| File | What it is | Size in game |
|---|---|---|
| `player.glb` | The hero (faces right, +X) | about 1.2 units tall |
| `bean.glb` | Pickup | about 0.6 units |
| `pigeon.glb` | Flying enemy (faces left, -X) | about 1.4 units wide |
| `spikeball.glb` | Wall obstacle | about 1.2 units |
| `bee.glb` | Chaser enemy (faces left) | about 1 unit |
| `gull.glb` | Dive-bomber (faces left) | about 1.6 units wide |
| `boss.glb` | King Pigeon (faces left; scaled up 2.6x in game) | about 1.4 units wide |

Tips: keep each under ~5k triangles, apply scale (Ctrl+A) before export, and use +Y up (the default glTF setting).
Flat colors with a toon look match the rest of the game best. If a file is missing, the game uses its built-in shape.
