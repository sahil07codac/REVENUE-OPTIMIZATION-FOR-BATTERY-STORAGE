# REVENUE-OPTIMIZATION-FOR-BATTERY-STORAGE

Modelling energy production is a core task for those developing, financing, and operating renewable energy projects. However, with battery storage, since no energy is being produced, the main consideration to model is when should the battery charge and discharge? To answer this we need to define what we mean by “should” and come up with a way to represent the physical attributes of battery storage and the commercial/market rules for how they are allowed to operate. This type of problem lends itself to a method called optimization. We define an objective (the “should”), apply constraints (which captures the physical and commercial/market attributes), and determine the decisions that lead to the best outcome. This case study describes the intuition behind optimization and how applying different constraints impacts results.


# BATTERY STORAGE BASICS
A battery energy storage system (BESS) is an electrochemical device that charges (or collects energy) from the grid or a power plant and then discharges that energy later to provide electricity or other grid services when needed. Key technical characteristics of BESS are:
●	Power Capacity (kW or MW) is the total possible instantaneous charge/discharge capability of the BESS
●	Energy Capacity (kWh or MWh) is the maximum amount of stored energy in the BESS
●	Storage Duration (h) is the number of hours BESS will take to discharge at its power capacity before depleting its energy capacity or vice versa
●	State of Charge, SOC (%) represents the battery’s present level of charge and ranges from completely discharged (0%) to fully charged (100%)
●	Charging efficiency (%) is the energy charged to the battery divided by the energy consumed from the grid
●	Discharging efficiency (%) is the energy supplied to the grid divided by the energy discharged by the battery
