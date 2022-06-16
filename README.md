# Qiao_et_al_Dose-response-alignment
Codes in the folder "coupled_without_feedback" are for simulating the system without feedback. 
The files with "mass" and "Hill" correspond to the mass action and Hill-function models, respectively.

For simulating the mass action (or Hill-function) model, do the following steps:
1. run server_mass_mGAP.m (or server_Hill_mGAP.m) to randomly sample the kinetic parameter and calculate the DoRA metric for each parameter set;
2. run plot_mass_sample.m (or plot_Hill_sample.m) to plot the upper panel in Figure 2B (or Figure 2D);
3. run plot_mass_server.m (or plot_Hill_server.m) to plot middle and bottom panels in Figure 2B (or Figure 2D) and the left panel in Figure 5B (or Figure 5D)


Codes in the folder "coupled_feedback" are for simulating the system with feedback. 
The files with "mass" and "Hill" correspond to the mass action and Hill-function models, respectively.

For simulating the mass action (or Hill-function) model, do the following steps:
1. run server_mass.m (or server_Hill_OR.m, server_Hill_AND.m ) to randomly sample the kinetic parameter and calculate the DoRA metric for each parameter set;
2. run plot_mass_sample.m (or plot_Hill_sample.m) to plot the upper panel in Figure 3B (or Figure 3D);
3. run plot_mass_server.m (or plot_Hill_server.m) to plot middle and bottom panels in Figure 3B (or Figure 3D), Figure 4A (or Figure 4C), and the right panel in Figure 5B (or Figure 5D)
