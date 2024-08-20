# Balanced-Neural-Network

Sparse random connected Balanced Neural Network
Network architecture:
*neurons 12500
*connection probability 10%

Balanced Neural Network.py simulats a balanced neural network by Brian simulator.

sim(g, nu_ext_over_nu_thr, sim_time, ax_spikes, ax_rates, rate_tick_step):
    
    """
    g -- relative inhibitory to excitatory synaptic strength
    nu_ext_over_nu_thr -- ratio of external stimulus rate to threshold rate
    sim_time -- simulation time
    ax_spikes -- matplotlib axes to plot spikes on
    ax_rates -- matplotlib axes to plot rates on
    rate_tick_step -- step size for rate axis ticks
    """

example:

"A": {
        "g": 3,
        "nu_ext_over_nu_thr": 2,
        "t_range": [500, 600],
        "rate_range": [0, 6000],
        "rate_tick_step": 1000,
        
![Figure_1](https://github.com/user-attachments/assets/7ab0edad-c288-4a3b-88a0-ac004215fd18)


"B": {
        "g": 2,
        "nu_ext_over_nu_thr": 4,
        "t_range": [1000, 1200],
        "rate_range": [0, 400],
        "rate_tick_step": 100,
    },

![Figure_2](https://github.com/user-attachments/assets/1561986f-b485-4d03-b1e6-c5f6e0cc10d0)


"D": {
        "g": 4.5,
        "nu_ext_over_nu_thr": 0.9,
        "t_range": [1000, 1200],
        "rate_range": [0, 250],
        "rate_tick_step": 50,
    },
![Figure_3](https://github.com/user-attachments/assets/04f3eaef-64c7-4d54-a1fa-9af408e8424d)

















    

