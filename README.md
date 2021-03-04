# Multiagent-Oscillator-Simulation
Python code to simulate the synchronization of oscillators using reinforcement learning. This is for the Synchronization of Cart Pole Systems using Reinforcement Learning senior project by Jakob Harig and Ryan Russell, with Dr. Jing Wang as the advisor, at Bradley University.

The oscillator is the preliminary model to test the multiagent synchronization using reinforcement learning for our project as the system is stable. Synchronization of oscillators is verified in simulation using both a linear multiagent controller and reinforcement learning controller. 

## Multiagent_Linear_Oscillator_Sim.py:
  
  Description: This python code simulates the synchronization of oscillators using a linear multiagent controller. This then simulation outputs the results to a mat file to be plotted and evaluated using MATLAB. 

  Commandline prompt to run: python Multiagent_Linear_Oscillator_Sim.py
  
  Output File: Linear_Oscillator_Results_{time}.mat

## Multiagent_Oscillator_Sim.py:

  Description: This python code simulates the synchronization of oscillators using an online reinforcement learning controller, utilizing a radial basis function. This then simulation outputs the results to a mat file to be plotted and evaluated using MATLAB. 

  Commandline prompt to run: python Multiagent_Oscillator_Sim.py
  
  Output File: Oscillator_Results_{time}.mat
