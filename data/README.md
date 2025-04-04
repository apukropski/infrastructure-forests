## Forest Cover Type

Dataset and Description Source: https://www.kaggle.com/uciml/forest-cover-type-dataset

> This dataset contains tree observations from four areas of the Roosevelt National Forest in Colorado. These areas represent forests with minimal human-caused disturbances, so that existing forest cover types are more a result of ecological processes rather than forest management practices. All observations are cartographic variables (no remote sensing) from 30 meter x 30 meter sections of forest. There are over half a million measurements total! This dataset includes information on tree type, shadow coverage, distance to nearby landmarks (roads etcetera), soil type, and local topography. Cover type data came from US Forest Service inventory information, while the cartographic variables used to predict cover type consisted of elevation, aspect, and other information derived from standard digital spatial data processed in a geographic information system (GIS)

### Background Information

| Feature                              | Data Type    | Measurement   | Description                                                                |
| ------------------------------------ | ------------ | ------------- | -------------------------------------------------------------------------- |
| Elevation                            | quantitative | meters        | Elevation in meters                                                        |
| Aspect                               | quantitative | azimuth       | Aspect in degrees azimuth                                                  |
| Slope                                | quantitative | degrees       | Slope in degrees                                                           |
| Horizontal Distance to Hydrology     | quantitative | meters        | Distance to nearest surface water features (horizontal)                    |
| Vertical Distance to Hydrology       | quantitative | meters        | Distance to nearest surface water features (vertical)                      |
| Horizontal Distance to Roadways      | quantitative | meters        | Distance to nearest roadway                                                |
| Hillshade at 9 am (summer solistice) | quantitative | 0 - 255 index | Hillshade index at 9 am                                                    |
| Hillshade at noon                    | quantitative | 0 - 255 index | Hillshade index at 12 pm (noon)                                            |
| Hillshade at 3 pm                    | quantitative | 0 - 255 index | Hillshade index at 3 pm                                                    |
| Distance to Fire Points              | quantitative | meters        | Distance to nearest wildfire ignition points                               |
| Wilderness Area                      | qualitative  | binary        | 0 (absence) / 1 (presence) indicating one of the four wilderness area type |
| Soil Type                            | qualitative  | binary        | 0 (absence) / 1 (presence) indicating one of the forty soil type           |
| Cover Type                           | qualitative  | integer       | Forest Cover Type Designation (1-7)                                        |

#### Cover Types / Trees

1 - Spruce/Fir<br>
2 - Lodgepole Pine<br>
3 - Ponderosa Pine<br>
4 - Cottonwood/Willow<br>
5 - Aspen<br>
6 - Douglas-fir<br>
7 - Krummholz<br>

#### Wilderness areas

1 - Rawah Wilderness Area<br>
2 - Neota Wilderness Area<br>
3 - Comanche Peak Wilderness Area<br>
4 - Cache la Poudre Wilderness Area<br>

As for primary major tree species in these areas:

- Neota would have spruce/fir (type 1), while
- Rawah and Comanche Peak would probably have lodgepole pine (type 2) as their primary species, followed by spruce/fir and aspen (type 5).
- Cache la Poudre would tend to have Ponderosa pine (type 3), Douglas-fir (type 6), and cottonwood/willow (type 4).

The Rawah and Comanche Peak areas would tend to be more typical of the overall dataset than either the Neota or Cache la Poudre, due to their assortment of tree species and range of predictive variable values (elevation, etc.) Cache la Poudre would probably be more unique than the others, due to its relatively low elevation range and species composition.

#### Soil Types

1 - Cathedral family - Rock outcrop complex, extremely stony<br>
2 - Vanet - Ratake families complex, very stony<br>
3 - Haploborolis - Rock outcrop complex, rubbly<br>
4 - Ratake family - Rock outcrop complex, rubbly<br>
5 - Vanet family - Rock outcrop complex complex, rubbly<br>
6 - Vanet - Wetmore families - Rock outcrop complex, stony<br>
7 - Gothic family<br>
8 - Supervisor - Limber families complex<br>
9 - Troutville family, very stony<br>
10 - Bullwark - Catamount families - Rock outcrop complex, rubbly<br>
11 - Bullwark - Catamount families - Rock land complex, rubbly<br>
12 - Legault family - Rock land complex, stony<br>
13 - Catamount family - Rock land - Bullwark family complex, rubbly<br>
14 - Pachic Argiborolis - Aquolis complex<br>
15 - unspecified in the USFS Soil and ELU Survey<br>
16 - Cryaquolis - Cryoborolis complex<br>
17 - Gateview family - Cryaquolis complex<br>
18 - Rogert family, very stony<br>
19 - Typic Cryaquolis - Borohemists complex<br>
20 - Typic Cryaquepts - Typic Cryaquolls complex<br>
21 - Typic Cryaquolls - Leighcan family, till substratum complex<br>
22 - Leighcan family, till substratum, extremely bouldery<br>
23 - Leighcan family, till substratum - Typic Cryaquolls complex<br>
24 - Leighcan family, extremely stony<br>
25 - Leighcan family, warm, extremely stony<br>
26 - Granile - Catamount families complex, very stony<br>
27 - Leighcan family, warm - Rock outcrop complex, extremely stony<br>
28 - Leighcan family - Rock outcrop complex, extremely stony<br>
29 - Como - Legault families complex, extremely stony<br>
30 - Como family - Rock land - Legault family complex, extremely stony<br>
31 - Leighcan - Catamount families complex, extremely stony<br>
32 - Catamount family - Rock outcrop - Leighcan family complex, extremely stony<br>
33 - Leighcan - Catamount families - Rock outcrop complex, extremely stony<br>
34 - Cryorthents - Rock land complex, extremely stony<br>
35 - Cryumbrepts - Rock outcrop - Cryaquepts complex<br>
36 - Bross family - Rock land - Cryumbrepts complex, extremely stony<br>
37 - Rock outcrop - Cryumbrepts - Cryorthents complex, extremely stony<br>
38 - Leighcan - Moran families - Cryaquolls complex, extremely stony<br>
39 - Moran family - Cryorthents - Leighcan family complex, extremely stony<br>
40 - Moran family - Cryorthents - Rock land complex, extremely stony<br>

### Acknowledgement

This dataset is part of the UCI Machine Learning Repository, and the original source can be found [here](https://archive.ics.uci.edu/ml/datasets/Covertype). The original database owners are Jock A. Blackard, Dr. Denis J. Dean, and Dr. Charles W. Anderson of the Remote Sensing and GIS Program at Colorado State University.
