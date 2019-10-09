# Drone-Routing-Optimization
Optimization of Capacitated Drone Routing Scheduling and Distribution of Vaccines in New York, New Jersey and Connecticut using CPLEX in AMPL.

The Center for Disease Control and Prevention (CDC) developed the power vaccination called NOSE for the relief of common cold, the main aim of this project is that the vaccine must be
transported immediately to the various nearby hospitals because of its short shelf life. For that to happen, we need the help of drones to ship the vaccines as soon as the vaccine is produced
by the laboratory. The initial step for this project was the data collection and selecting the hospitals to which the vaccine will be supplied. The objective function is to minimize the number of drones used to supply the vaccines to the 20 nearby hospitals. Dynamic programming was employed to satisfy the demand of the vaccines across every hour. Capacitated vehicle routing problem was used to decide the routes of the drones while MTZ and sub-tour elimination was used to solve the problem. Following this, techiques like relaxation, heuristics (add and swap) were used to obtain the optimized results.
