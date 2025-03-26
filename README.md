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
