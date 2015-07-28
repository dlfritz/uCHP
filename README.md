# uCHP
MicroCHP Simulation

This simulation is a modular micro CHP code designed in Scipy to act as an 
interchangeable CHP simulation adjustable to different system layouts. Each 
module is written as a function with its own inputs, all interchangable modules 
can be exchanged in a "plug and play" fashion. Hybrid power generation units 
involving energy storage can by any combination of Sterling engines, internal 
combustion engines, gas turbines, fuel cells, photo voltaic and wind turbines. 

# What is included?

This package is currently under development and none of the functions are in 
working order. The current files in this package are:
uCHP_Randbedingung.dat --> Boundary condition input file
uCHP_Simulation.py     --> Main simulation file
uCHP_Thermalspeicher.py--> Heat transfer module
