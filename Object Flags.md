## Flags for objects

## VERY INCOMPLETE

### [0] Goomba-Galoomba/Goombrat-Goombud
| Flag   | Description       |
|--------|-------------------|
| 0x2    | With wings        |
| 0x4    | Goombrat-Goombud  |
| 0x4000 | Giant             |
| 0x8000 | With parachute    |


### [8] Coin/Frozen Coin
| Flag   | Description       |
|--------|-------------------|
| 0x2    | With wings        |
| 0x4    | Frozen            |
| 0x8000 | With parachute    |

### [9] Pipe
| Flag    | Description      |
|---------|------------------|
| 0x20    | Direction: left  |
| 0x40    | Direction: up    |
| 0x40000 | Color: red       |
| 0x80000 | Color: blue      |

Pipe default color is green.  
If both flags 0x40000 and 0x80000 are set, pipe color is yellow.  
  
Pipe default direction is right.  
If both flags 0x20 and 0x40 are set, pipe direction is down.

### [20] Super Mushroom/Master Sword
| Flag    | Description    |
|---------|----------------|
| 0x2     | With wings     |
| 0x4     | Master Sword   |
| 0x8000  | With parachute |

### [34] Fire Flower/Superball Flower
| Flag    | Description       |
|---------|-------------------|
| 0x2     | With wings        |
| 0x4     | Superball Flower  |
| 0x8000  | With parachute    |
| 0x40000 | Mushroom modifier |

### [44] Theme specific items (Big Mushroom/Super Leaf/Cape Feather/Propeller Mushroom/Super Bell)
| Flag    | Description       |
|---------|-------------------|
| 0x2     | With wings        |
| 0x8000  | With parachute    |
| 0x40000 | Mushroom modifier |

### [55] Warp Door
| Flag    | Description |
|---------|-------------|
| 0x40000 | P-Door      |
| 0x80000 | Key Door    |

Door pair ID also seems to be flags? Each door has +0x100000 (default door with ID 0 has flags 0x6000040, ID 1 has flags 0x6100040, etc too ID 0x700000)

### [70] Big Coin
| Flag    | Description                  |
|---------|------------------------------|
| 0x2     | With wings                   |
| 0x8000  | With parachute               |
| 0x40000 | Value: 30                    |
| 0x80000 | Value: 50                    |

Big Coin default value is 10.

### [74] Spike/Spike Ball
| Flag | Description |
|------|-------------|
| 0x4  | Only Ball   |

### [79] P-Block
| Flag | Description |
|------|-------------|
| 0x4  | Enabled     |