Programming Exercise

The Game of “Life”

This is a useful exercise (though it’s not a realistic or meaningful program) in order to improve your programming skills and experience.
“Life” is actually a simulation rather than a game with real players. It is based on a two dimensional array. Every cell of the array can be either alive or dead. Every cycle of the game represents a “generation”. In every cycle the population changes according to the following specific rules:

1.	Every cell has 8 neighbors (the 8 surrounding cells). The boundary cells have fewer neighbors.
2.	Alive cells that have no neighbor alive or have only one neighbor alive will die of loneliness in the next cycle.
3.	Alive cells that have 4 or more neighbors alive will die of overcrowding in the next cycle.
4.	Alive cells that have 2 or 3 neighbors alive remain alive in the next cycle.
5.	Dead cells that have exactly 3 alive neighbors will change to alive in the next cycle.
6.	All births and deaths take place simultaneously. This way dying cells cannot help to give birth to other cells, or prevent the death of other cells. Also cells born in one cycle do not affect births and deaths of the same cycle.

