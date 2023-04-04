# STAT650_Project_Pokemon
This is the repository of final project for STAT 650 (Advanced R in Data Science)

The dataset used was ["The Complete Pokemon Dataset"](https://www.kaggle.com/datasets/rounakbanik/pokemon) from Kaggle user Rounak Banik. The data contains information on pokemon from the game *Pokemon Go*. The data technically isn't complete Pokemon dataset as it is limited to the Pokemon that were already introduced in and before 2017.

The data has columns that include the following:

* `attack`, `defense`, `speed`, `hp`, `sp_attack`, `sp_defense`

  Numeric columns representing attributes used in combat.
  
* `base_egg_steps`, `base_happiness`

  Numeric columns representing base values for Pokemon attributes.
  
* `capture_rate`

  8-bit integer column that is used to calculate the probability that a Pokemon is caught.
  
* `height_m`

  Numeric column representing the height of the Pokemon in meters.
  
* `name`

  Character column containing the Pokemon's official English name. This is also a unique identifier.
  
* `percentage_male`

  Numeric column representing the percent of the pokemon of a species that are male. Pokemon species without sex have `NA` values in this column.
  
* `type1`, `type2`

  Character columns representing the primary and secondary types of the pokemon respectively.
  
* `weight_kg`

  Numeric column representing the weight of the Pokemon in kg.
  
* `generation`

  Factor representing the generation in which the Pokemon was introduced. This dataset only contains up to Generation 7 (i.e. Pokemon from *Ultra Sun*, *Ultra Moon*, and previous titles).
  
* `is_legendary`

  Logical column that is true when the Pokemon is legendary and false otherwise.

* `classification`

  Character column giving the biological classification of the Pokemon.

* `experience_growth`

  I am still not sure what this does.
