# Mechanical Engineering Design and Analysis - Gearbox in Wind Turbine
<p align="center">
  <img width="500" src="https://github.com/kiettran499/Wind-Turbine-Project-Mechanical_Design/blob/main/The%20final%20design%20with%20bedplate_3D%20model.png">

## Description

- The idea of this assignment - Mechanical Engineering Design and Analysis is working on an industrial engineering project as an engineer in a company. The task involves designing gearbox in a horizontal axis wind turbines for an offshore wind farm that is around 20 kilometers from the coast. For the system which I’m going to design, the wind turbine will be the simplified version.
- There are some primary design specifications for the wind turbine:
- Weight and Size: Optimised as minimum.
- Material Selection requires justification based on operating conditions.
- Gearbox:
  - Transmission ratio, Gear type and arrangement must meet operational conditions.
- Shaft Arrangement:
  - The main shaft and high-speed shaft should be in line.
  - The main shaft and high-speed shaft are approximately 0.15 m and 0.1 m long 
    respectively.
  - The bearing selection and shaft key must meet Operational Conditions. The axial load    (thrust) on the bearing from a drag to lift ratio of the blades equal to 0.2. The
  centre of lift of the blades is 10m from the centreline of the hub.
- Operational Condition:
  - At maximum operating wind speed the blades are expected to rotate at 60 RPM while the
  generator turns at 750 rpm to provide 3 MW (Maximum) of useful power. Overall
  efficiency of the powertrain including generator is 80%. 
- Life: The system is designed to operate for 8 years continuously.
- Reliability: 99% for all parts.
- Safety factor: 2 for all parts.
- Other factors and coefficients are according to your design selection.


## Conceptual Design

- For the material of the shafts and gears of the wind turbine, we select EN8 and 080M40 steel. It is a medium carbon engineering steel with good mechanical qualities that is widely used in the construction of mechanical parts including general axles and shafts, gears, bolts, and stud bolts. In addition, we should select a stronger material for the key, which will prevent it from breaking during system operation. EN8 and 080M40 steel with hardened and tempered + turned or ground condition is selected.
- After doing calculations of the components, we put them together as indicated in the diagram below.
<p align="center">
  <img width="500" src="https://github.com/kiettran499/Wind-Turbine-Project-Mechanical_Design/blob/main/The%20final%20design%20with%20bedplate_2D%20drawning.png">
</p>

- Gearbox Assembly (Animation GIF)
<p align="center">
  <img width="500" src="https://github.com/kiettran499/Wind-Turbine-Project-Mechanical_Design/blob/main/Gearbox_assembly%20.gif">
  
## Simulation and System Analysis

### Motion analysis
- By using Motion Analysis on SolidWorks, we can run the whole system and see the angular velocity of the output which is the high-speed shaft. Firstly, we apply a rotor, which has angular velocity of 60 RPM, to the main shaft. The expected angular velocity of the output is 750 RPM or 450 rad/s.
<p align="center">
  <img width="500" src="https://github.com/kiettran499/Wind-Turbine-Project-Mechanical_Design/blob/main/MotionAnalysis.png">
</p>

- Gearbox Motion Simulation (Animation GIF)
<p align="center">
  <img width="500" src="https://github.com/kiettran499/Wind-Turbine-Project-Mechanical_Design/blob/main/Gearbox_MotionAnalysis.gif">
  
### FEA simulation
- After shafts are designed by using Solidworks, we will analyze the FEA using Simulation function. Images below show the Mesh, Stress, Deformation, and Strain analysis of components.
<p align="center">
  <img width="500" src="https://github.com/kiettran499/Wind-Turbine-Project-Mechanical_Design/blob/main/FEA%20analysis%20of%20main%20shaft.png">
</p>
<p align="center">
  <img width="500" src="https://github.com/kiettran499/Wind-Turbine-Project-Mechanical_Design/blob/main/FEA%20analysis%20of%20Gear1.png">




