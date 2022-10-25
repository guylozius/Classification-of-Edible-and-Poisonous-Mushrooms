# Classification-of-Edible-and-Poisonous-Mushrooms 
## Making and Tuning a Model for Production
**Guy Lozius**:

### Business problem:
The goal is to create a model that is efficient at determining if a mushroom is edible or poisonous, and then recommend it for production and the stakeholder. <br/>
### Data:
Dataset source: (https://www.kaggle.com/datasets/uciml/mushroom-classification)
| Columns                  | Description                               | Values                                                                               |
|--------------------------|-------------------------------------------|--------------------------------------------------------------------------------------|
| Classes                  | If the mushrooms are edible or poisonous. |  edible, poisonous                                                                   |
| cap-shape                | The Cap shape of mushroom.                | Bell, conical, convex, flat, knobbed, sunken                                         |
| cap-surface              | The texture of the mushroom cap.          | Fibrous, grooves ,scaly, smooth                                                      |
| cap-color                | The color of the mushroom cap.            | Brown, buff, cinnamon, gray, green, pink, purple ,red,white, yellow                  |
| bruises                  | If the mushroom has bruises or not.       | Bruises, No-Bruises                                                                  |
| Odor                     | The odor of the mushroom.                 | Almond, anise, creosote, fishy,  foul, musty,  none, pungent, spicy                  |
| Gill-Attachment:         | The Gill attachment states of mushroom.   | Attached,descending,free,notched=n                                                   |
| Gill-spacing             | The spacing between the gills.            | Close, Crowded, Distant                                                              |
| Gill-size                | The gill size of mushroom.                | Broad, Narrow                                                                        |
| Gill-color:              | The color of gill.                        | Black, brown, buff, chocolate, gray, green, orange, pink, purple, red, white, yellow |
| Stalk-shape              | The stem shape of a mushroom.             | Enlarging, tapering                                                                  |
| stalk-root:              | The type of root the mushroom has.        | Bulbous, club, cup, equal, rhizomorphs                                               |
| stalk-surface-above-ring | Texture of the ring above the stalk .     | Fibrous, scaly, silky, smooth                                                        |
| stalk-surface-below-ring | Texture of the ring below the stalk.      | Fibrous, scaly, silky, smooth                                                        |
| stalk-color-above-ring:  | Color of the ring above the stalk .       | Brown, buff, cinnamon, gray, orange, pink, red, white, yellow.                       |
| stalk-color-below-ring:  | Color of the ring below the stalk .       | Brown, buff, cinnamon, gray, orange, pink, red, white, yellow.                       |
| Veil_type:               | Veil type of mushroom                     | partial,universal                                                                    |
| Veil-color               | Color of the veil                         | Brown, orange, white, yellow                                                         |
| ring-number:             | The number of ring                        | None, One, Two                                                                       |
| ring-type:               | The type of ring                          | Cobwebby,Evanescent, Flaring, large, none, pendant, sheathing, zone                  |
| spore-print-color:       | The color print from spore.               | Black, brown, buff, chocolate, green, orange, purple, white, yellow                  |
| population:              | How many mushrooms grows.                 | Abundant, clustered, numerous, scattered, several, solitary.                         |
| habitat:                 | The type places the mushroom grows at.    | Grasses, leaves, meadows, paths, urban, waste, woods                                 |
## The model Recommendation.
The model I picked for "production" is  LogisticRegression for classification of poisonous and edible mushroom because it is fastest and with high accuracy, but the dataset is made with synthetic mushroom base on average, which can lead to data leakage causing all models to have high accuracy, so I will not recommend any model for production.
