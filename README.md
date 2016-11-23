# PowerToAll
An attempt at a minecraft mod for semi-realistic late-game electricity.


## Concept:

Keep methods modular and simple. Every block has 1 function and can interact with the world (Through a GUI or otherwise). Do not make vanilla blocks obselete.

#### Alterations to vanilla:
Furnaces require to be heated to different temperatures for different items. This allows simultaneously for more efficient small scale smelting of low-heat items (such as food) and large scale smelting of high-heat items (such as ores). Furnaces no longer accept fuel, and require to be fueled from external sources.

### PowerGen
#### Basic structure:
Heat source --> Water boiler --> Movement --> Dynamo --> Electricity
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
Electricity has to be converted to a more appropriate energy form in order to be used.

#### Heating element:
Because of the changes to furnaces. Heat for furnaces and other operations has to come from somewhere. The heating element accepts electricity to generate heat for adjacent blocks. 

#### Firepit:
Because of the changes to furnaces. Heat for furnaces and other operations has to come from somewhere. The firepit accepts fuel to generate heat for adjacent blocks. 

