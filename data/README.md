# Data
-   **[pokemon_df.csv]**: A dataset of Pokemon information sourced from {pokemon} (CRAN | github), an R package which provides Pokemon information in both English and Brazilian Portuguese. The dataset contains 949 rows and 22 columns, including information such as the Pokemon’s name, ID, height, weight, stats, type, and more. Came from TidyTudesdays https://github.com/rfordatascience/tidytuesday/tree/main/data/2025/2025-04-01 

# Codebook for [pokemon_df.csv] Dataset

## 📊 Dataset Codebook

This data dictionary documents the structure, column types, and descriptions for the variables included in the Pokémon dataset.

| Variable Name | Data Type | Description | Example / Notes |
| :--- | :--- | :--- | :--- |
| **id** | Numeric | A unique identifier for each row in the dataset. | `1`, `2`, `10001` |
| **pokemon** | String | The common name of the Pokémon or specific form variant. | `bulbasaur`, `charizard-mega-x` |
| **species_id** | Numeric | The National Pokédex species index number. | `1` (for both normal and Mega Bulbasaur forms) |
| **height** | Numeric | The height of the Pokémon measured in meters. | `0.7` |
| **weight** | Numeric | The weight of the Pokémon measured in kilograms. | `6.9` |
| **base_experience** | Numeric | The base amount of EXP yielded when defeating this Pokémon. | `64` |
| **type_1** | Categorical | The primary elemental type of the Pokémon. | `grass`, `fire`, `water`, `bug` |
| **type_2** | Categorical | The secondary elemental type (if applicable). | `poison`, `flying` (`NA` if single-typed) |
| **hp** | Numeric | Base Hit Points stat. Determines maximum health. | `45` |
| **attack** | Numeric | Base Attack stat. Affects physical move damage. | `49` |
| **defense** | Numeric | Base Defense stat. Affects resistance to physical moves. | `49` |
| **special_attack** | Numeric | Base Special Attack stat. Affects special move damage. | `65` |
| **special_defense** | Numeric | Base Special Defense stat. Affects resistance to special moves. | `65` |
| **speed** | Numeric | Base Speed stat. Determines turn order in battle. | `45` |
| **color_1** | String (Hex) | The primary hex color code associated with the Pokémon's design. | `#78C850` |
| **color_2** | String (Hex) | The secondary hex color code associated with the design. | `#A040A0` (`NA` if single-toned) |
| **color_f** | String (Hex) | An additional background or accent hex color code. | `#81A763` |
| **egg_group_1** | Categorical | The primary breeding category group. | `monster`, `plant`, `no-eggs` |
| **egg_group_2** | Categorical | The secondary breeding category group (if applicable). | `dragon`, `water1` (`NA` if none) |
| **url_icon** | String | Relative URL pathway to the icon asset. | `//archives.bulbagarden...` |
| **generation_id** | Numeric | The generation number in which the Pokémon was introduced. | `1`, `2`, `3`, `4`, `5`, `6`, `7` |
| **url_image** | String | Full web link URL to the high-resolution image asset. | `https://githubusercontent.com...` |



