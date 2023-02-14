Info on modding can be found here:
https://drive.google.com/file/d/1_OesG68HtJ4CwyHK7M72hQDOaCjeqgqT/view
Thanks to Jake, Superwutz, and Bendigeidfran for the documentation!

---

GenerationSettlement.txt config defaults, explanations, and ranges:

CAVE_AMOUNT: 0.16,
CAVE_AMOUNT affects the frequency with which caves will be generated in mountainous
areas. A value of zero would prevent caves from generating at all. It is a float value up to 1.0.

CAVE_SIZE: 0.5,
CAVE_SIZE affects the size of caves generated in mountainous areas. A value of zero would
prevent caves from generating at all. It is a float value up to 1.0.

CAVE_TUNNELS: 0.2,
CAVE_TUNNELS affects the frequency of tunnels generated connecting caves to the surface
and each other. It is a float value up to 1.0.

MOUNTAIN_SIZE: 0.2,
MOUNTAIN_SIZE affects the size of mountains generated on local maps that have one. It is
a float value up to 1.0.

MOUNTAIN_RANDOM: 0.2,
MOUNTAIN_RANDOM affects how many very tiny mountains across the local map
regardless of how mountainous the region is. It is a float value up to 1.0.

RIVER_WIDTH: 6,
RIVER_WIDTH affects the width of rivers on maps that generate them. It is an integer value
from 1 to 6.

LAKE_SIZE: 0.2,
LAKE_SIZE affects the size of lakes generated on maps that have them. It is a float value up
to 1.0.

LAKE_SMALL: 0.5,
LAKE_SMALL affects how many tiny lakes are generated on all maps, regardless of how
watery the map is. It is a float value up to 1.0.

LAKE_ISLANDS: 0.3,
LAKE_SMALL affects the size or frequency of islands generated in lakes, on maps that have
them. It is a float value up to 1.0.FOREST_AMOUNT: 0.7,

FOREST_AMOUNT: 0.7,
FOREST_AMOUNT affects the number of forests that generate on maps that have them. It is
a float value up to 1.0.

FOREST_DENSITY: 0.8,
FOREST_DENSITY affects the density of forests that generate on maps that have them. It is
a float value up to 1.0.

MINERALS_AMOUNT: 0.3,
MINERALS_AMOUNT affects the number of stone resources generated on the map, this
specifically affects the manually gathered materials rather than the ones that require a
mine.. It is a float value up to 1.0.

EDIBLES_AMOUNT: 1.0,
EDIBLES_AMOUNT affects the number of gatherable plants generated on the map, this
specifically affects the manually gathered plants, including non-edibles such as cotton. It is a
float value up to 1.0.