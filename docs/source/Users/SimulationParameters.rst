.. _Users-SimulationParameters:

Simulation Parameters
=====================

The first step of the network creation is defining the simulation parameters. Here, we define basic parameters for the simulation such as timestamp size, no.of neurons, units for simulation, how long to run the simulation etc. 

The user has to choose wether to have all the neurons with the same model or have a combination of different models. In case of different model option, the user has to choose how many of the neurons will use a different model.  

+-----------------------------+---------------------------------------------------------+
| Parameter                   | Description                                             |
+=============================+=========================================================+
| Timestamp                   | Time bin size                                           |
+-----------------------------+---------------------------------------------------------+
| No.of Neurons               | Total no of neurons                                     | 
+-----------------------------+---------------------------------------------------------+
| Are all neurons same model? | Same models for all the neurons or use different models |
+-----------------------------+---------------------------------------------------------+
| How many different models?  | If different model is chosen                            |
+-----------------------------+---------------------------------------------------------+
| Simulation units            | either in milliseconds or seconds                       | 
+-----------------------------+---------------------------------------------------------+
| Simulation time             | How long to run the simulation in units selected earlier|
+-----------------------------+---------------------------------------------------------+
| Watchdog time               | Time in ms to wait for a packet				|
+-----------------------------+---------------------------------------------------------+
