Add your own prop thumbnails in this folder. The image filename must match the prop model name.

Supported formats:
- <model>.png  (recommended)
- <model>.jpg
- <model>.webp

Examples:
- prop_barrier_work05.png   -> matches model "prop_barrier_work05"
- prop_chair_01a.png        -> matches model "prop_chair_01a"
- prop_tree_pine_01.webp    -> matches model "prop_tree_pine_01"

Image Resolution Order:
1. Local files in this folder (highest priority)
2. PlebMasters Forge API thumbnails (automatic, for props without local images)
3. Config.PropImageBaseURL remote images
4. Auto-generated SVG fallback placeholder

To add a new prop:
1. Add the prop entry in config.lua under Config.Props
2. Drop a matching .png image in this folder (named exactly like the model)
3. The menu will automatically display it
