# Computational Neuroscience Course - 2022

# Neuronal Modeling and Simulation 

## Course Overview
This course focuses on the implementation and analysis of various neuronal models and learning mechanisms, providing a deeper understanding of how neurons behave individually and within populations. The primary goal is to simulate neuron behavior, explore synaptic plasticity, and study neural interactions within networks through computational experiments. Python, along with key libraries such as `numpy` and `matplotlib`, is used for coding and visualizing the results.

## Course Assignments

### Assignment 1: Neuronal Model Implementation
In this assignment, the focus was on implementing three neuron models:
- **LIF (Leaky Integrate-and-Fire)**
- **ALIF (Adaptive Leaky Integrate-and-Fire)**
- **AELIF (Adaptive Exponential Leaky Integrate-and-Fire)**

The aim was to simulate the response of these models to different types of input currents (constant, linear, and sinusoidal) and analyze their behavior by plotting voltage over time (t_U), input current (t_I), and firing rates (I_F). The experiment explored how varying model parameters influenced neuron spiking and frequency.

### Assignment 2: Neuronal Population Simulation
Building upon the first assignment, the second exercise required simulating **neuronal populations**. The goals were:
- **Neuron-to-Neuron Connection**: Create connections between two neurons and apply different types of excitatory and inhibitory currents, analyzing their interactions.
- **Neuronal Population**: Simulate a population of neurons, including both excitatory and inhibitory types, and observe how they behave collectively using **raster plots** to track spiking activity.
- **Inter-Population Connection**: Finally, connect multiple neuron populations, examine their interaction over time, and measure how spiking in one population affects another.

### Assignment 3: Learning Processes in Neurons
The third assignment delved into **neural learning** using **Spike-Timing Dependent Plasticity (STDP)**. It involved two main experiments:
- **STDP Learning**: A network of three interconnected neurons was tested with different input currents (constant, sinusoidal, and step-function). The goal was to explore how the timing of spikes affected synaptic weight changes.
- **Reward-Based STDP Learning**: A simple input-output neural network was trained using reward-based STDP. The synaptic weights were adjusted based on rewards to train the network to produce correct spike outputs. A dataset with predefined input currents and expected spike outputs was used for training and testing.


The main objectives of this course are:
Implement and simulate different neuronal models (LIF, ALIF, AELIF), analyze neuronal behavior under varying input conditions, understand neuronal population dynamics and interactions, and explore neural learning mechanisms using STDP and reward-based learning.






