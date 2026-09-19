# Dataset statistics

Derived from the 1,000-dataset inventory (`datasets.csv` / `datasets.json`).

## Counts

| Quantity | Value |
|---|---|
| Total datasets | 1000 |
| Categories | 50 |
| Datasets per category | 20 |
| Unique IDs | DS0001–DS1000 |

## Notes on derived tallies

Modality and task matrices in the README use **primary-home tags**. A multimodal dataset (e.g. nuScenes) is counted once in CAT16 even though it contains cameras, LiDAR, radar, and IMU.

License field policy:
- SPDX or named license copied from a card when seen
- `research` = project page states research use without a clean SPDX string
- `UNKNOWN` = not verified at freeze time
- Government `public USG` / Copernicus attribution licenses are common in CAT30–37

Synthetic vs real:
- Real: measured or human-captured
- Synthetic: simulation, DFT, procedural render, game engine
- Hybrid: paired sim+real, web-scale captions on real photos, reanalysis (model+obs)

Do not treat these descriptive bins as a ranking.
