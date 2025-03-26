# Initial Thoughts

Getting your hands on brushless DC motors is fairly easy nowadays. Setting the motors up for hobby projects is easy and configuration of the ESC via software is done using simple programs or even automatically. 
What requires more time and effort however, is the configuration of the hardware, mainly the motor itself. This is why I try to discover the possibilities of constructing custom BLDC motors and evaluate their performance in this repository. 

## Choice of motor type

After some initial research I reached the conclusion, that the motor type discussed here will be the permanent magnet axial flux motor (PM-AFM). This has numerous reasons:

- Ease of manufacturing
  - The use of an iron core to concentrate magnetic flux can be avoided without a significant efficiency decrease
  - Winding the copper wire is simplified, as no complex geometries are required to achieve coreless windings (in contrast to radial flux motors, that require more intricate wire geometries e.g. faulhaber winding)
  - the flat geometry of AFM allows the use of sheet metal parts (or other non-metallic materials) that can easily be manufactured on simple semi-professional CNC routers for cheap
- high power density
  - The elimination of bulky iron cores decreases overall weight, as all copper windings can be placed very close to the permanent magnets
- improved dynamics
  - reduced weight in the rotor can lead to highly dynamic motors, if the copper windings are used as a rotor

## Acknowledgements

My interest for PM-AFM was sparked by numerous articles and projects on this kind of motor. A selection is provided below:

- [Coreless Axial Flux Motors, Ben Katz](https://build-its-inprogress.blogspot.com/2015/02/coreless-axial-flux-motors.html)
- [Ironless Axial Flux Motor, Caden Kraft](https://cadenkraft.com/designing-a-coreless-axial-flux-motor-part-1/)
- [Axial-flux permanent-magnet machine modeling, design, simulation and analysis, A. Mahmoudi, N. Abd Rahim, W. Ping Hew](https://www.researchgate.net/publication/228847506_Axial-flux_permanent-magnet_machine_modeling_design_simulation_and_analysis)

## Choice of Motor Geometry

Numerous factors can influence the motor performance, efficiency and manufacturing process.

### Rotor / Stator configuration

PM-AFM commonly use either a double-rotor single-stator or double-stator single-rotor design, to achieve symmetrical magnetic flux and mechanical properties. To mitigate the need for a slip ring a double-rotor single-stator design was used, with the permanent magnets beeing placed on the rotor. In the future other geometries might be explored.

### 
