# February 5th 2025



### SPS

1. need to design a v3 SPS:

   - easier alignment of punches to reduce shearing (large kinematic couplings?)
   - more sheet metal, less CNC machining
   - maybe design a tool for loading / unloading so you don't need to put your fingers in the chamber?
   - better data collection for pressure/temp ramping and dwell

   **I can buy all the parts for this from sendcutsend / JLCCNC**

   

2. more attempts at transparent MgO / YO
   - keep track of pressure/temp for each experiment and put in vials and label vials
   - ship to Max for CT measurements
   
3. working towards transparent Yb:YCOB (Yb:YCa4O(BO3)3)
   1. can start with LiSr4(BO3)3: https://www.sciencedirect.com/science/article/abs/pii/S0272884222005156
4. side quest: sintering cenosphere foam: https://www.semanticscholar.org/paper/Study-of-Lightweight-Ceramic-Matrix-Less-Syntactic-Eiduks-Drunka/3bc6e8e26cf50e9c2520c0d5dd94a80c7176b147

**buy the precursors you need and invoice Max**

### Thin Film

1. machining for magnetron head (and design so that it fits self-contained on a KF50 flange)
   1. I would work from the Andrew Seltzman design
2. design larger PLD chamber that can fit larger substrate (e.g. 4'' silicon wafer), and magnetron head / PLD target + QCM 
3. figure out what components are needed to install QCM

### Nanopositioner

1. machine aluminum (or stainless) parts for Y stage
2. characterize motion accuracy and precision
3. write Python library that uses PySerial for control

### Litho

1. discuss with Max/BreakingTaps/Hacker Fab to determine optimal schema for litho stepper
   1. options: projector (16K LCD screen), DMD (the TI chip), galvo + f/theta lens, or R/Theta spinning stage
2. design & spec BOM for 1um minimum feature size 

### Chip Design

1. gdsfactory / klayout to design a simple transistor that can be made using our tools (+ wet etch, probably)



### side quests

1. try steel -> alumina brazing with Cusil braze in Luke's vacuum furnace & test vacuum capabilities
1. make the website look nicer (you can use my bolt.new)