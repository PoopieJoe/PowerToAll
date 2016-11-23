# PowerToAll
An attempt at a minecraft mod for semi-realistic late-game electricity.


## Concept:

Keep methods modular and simple. Every block has 1 function and can interact with the world (Through a GUI or otherwise). Do not make vanilla blocks obselete. Items without direct use should be avoided as much as possible (i.e. items only used in crafting).

In essence this mod adds 3 different power systems: Heat energy, mechanical energy and electrical energy, and ways to convert one to the other. Also machines are added which work off of one of these systems. With only a few inefficiënt ways to store energy, it is required to set up an efficiënt and reliable power generation system, to allow all of your machines to work consistently.

#### Alterations to vanilla:
Furnaces require to be heated to different temperatures for different items. This allows simultaneously for more efficient small scale smelting of low-heat items (such as food) and large scale smelting of high-heat items (such as ores). Furnaces no longer accept fuel, and require to be fueled from external sources.

### PowerGen
#### Basic structure:
Heat source --> Boiler --> Movement --> Dynamo --> Electricity

A heat source heats a water boiler to generate steam, which drives a turbine. The rotating movement powers a dynamo to generate electricity.

Different heat and movement sources can be used within a system. The water boiler and dynamo can be scaled up to increase production through multiblocks.

#### Heat sources:
- Fuel (Through ignition)
    - Coal
    - Biomass
- Solar (Through mirrors)

#### Movement:
- Player movement
    - Hand Crank
    - Treadmill
- Mill
    - Wind
    - Water
- Turbine

### Machinery
Every machine uses one particular kind of energy.

#### Heating element:
The heating element accepts electricity to generate heat for adjacent blocks. It can be heated by other Heating elements.

#### Heat conductor:
Pipe which conducts heat with less loss over distance. Heats adjacent blocks.

#### Firepit:
The firepit accepts fuel to generate heat for adjacent blocks. 

#### Solar mirror:
Solar mirrors provide heat to the block they point toward, given that they have a clear view to the sky, and it is daytime. One mirror does not provide much heat.

#### Boiler:
A multiblock structure. Basically a large tank that, when heated far enough, will expel steam through the top.

#### Pipe:
A simple pipe that moves fluids.

#### Nozzle:
A pipe which sprays it's contents out.

#### Mill:
A mill that's turned by water flowing on top of it, or from steam forcing it to turn.

#### Windmill:
A mill that's turned by the wind in the sky.

#### Hand Crank:
By holding right mouse button on it, the player turns an axis.

#### Treadmill:
By running or sprinting on a rotating platform, the player turns an axis.

#### Axis:
Axis which transfers rotation.

#### Dynamo:
A multiblock structure. Converts mechanical energy to electrical energy through induction.

#### Cable:
Conducts electricity.

#### Electrical Motor:
Converts electrical energy to mechanical energy through induction.

#### Crusher:
Crushes large rocks and ores into smaller components. Uses mechanical energy.  
- Stone, cobblestone, granite, etc. get crushed into gravel and rock dust.
- Metal ores get crushed into their respective gravel ores (with a chance of getting more than one) and some rock dust.
- Gem ores get crushed into their respective gems and some rock dust.

#### Grinder:
Grinds smalls item and fine materials into smaller components. Uses mechanical energy.  
- Gravel gets ground into flint, sand and rock dust.
- Gravel ores get ground into flint, metal dust (with a chance of getting more than one) and rock dust.
- Sand gets ground into rock dust.

#### Pump:
Uses mechanical energy to pump liquids from the world or an inventory into a pipe.

#### Tank:
Stores liquids. Duh. Extract from the bottom with a pump.

