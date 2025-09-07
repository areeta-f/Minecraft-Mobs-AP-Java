# Minecraft Mob Data Analysis

## Dataset Source
- **Source:** [Minecraft Blocks, Items, Mobs, Biomes, etc.](https://www.kaggle.com/datasets/madelinee/minecraft-blocks-items-mobs-biomes-etc?select=Mobs.csv) by MadelineE
- **License:** CC0: Public Domain

## What Each Entry Represents
Each row represents a single Minecraft mob and relevant information (name, behavior type, health, and maximum damage)

## Mob Class
- If we designed a Java class that relates to this data, each object would require fields about its name, behavior type, total health points, and the maximum damage it can deal in one hit.
- Methods include battle, which would compare health points and max damage for two mobs and calculate who would win; fight, between a player and a mob; feed, and spawn mobs.

## UML Diagram

| **Mob**         |
|-----------------|
|String name|
|String behavior|
|int health|
|int maxDamage|
|countCommas()|
|getColumnValue()|
|chooseDataPoint()|
|analyzeData()|
