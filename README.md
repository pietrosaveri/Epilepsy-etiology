# Brain Modeling Project: Epilepsy Etiology  

### A Study on the Principles Leading to Seizure Events  

## Authors  
<p align="center"> <a href="https://github.com/PietroSaveri"> <img src="https://github.com/PietroSaveri.png" width="100" height="100" style="border-radius: 50%;" alt="Pietro Saveri"/> </a> <br> <b>Pietro Saveri</b> </p> <p align="center"> <a href="https://github.com/SebaPietra"> <img src="https://github.com/SebaPietra.png" width="100" height="100" style="border-radius: 50%;" alt="Sebastiano Pietrasanta"/> </a> <br> <b>Sebastiano Pietrasanta</b> </p> <p align="center"> <a href="https://github.com/MatteoSalami"> <img src="https://github.com/M4tteoo.png" width="100" height="100" style="border-radius: 50%;" alt="Matteo Salami"/> </a> <br> <b>Matteo Salami</b> </p>

## Overview  
This project investigates the mechanisms underlying epileptic seizures, both at the **microscale** (single-neuron level) and **mesoscale** (neuronal population level). Our aim is to model seizure activity using a biologically inspired approach, analyzing the **ion channel dynamics** of individual neurons and the **network interactions** in the hippocampus and neocortex.  

## Methodology  

### Microscale: Hodgkin-Huxley Model  
We employed the **Hodgkin-Huxley model** to simulate single-neuron activity, analyzing the role of **sodium (Na⁺) and potassium (K⁺) channels** in seizure generation. A key observation was that **impaired Na⁺ inactivation and reduced K⁺ outflow** contribute to sustained depolarization, leading to excessive firing of action potentials.  

### Mesoscale: Wendling Model  
We implemented the **Wendling model**, which describes interactions among three types of neurons:  
- **Excitatory pyramidal cells**  
- **Slow inhibitory interneurons**  
- **Fast inhibitory interneurons**  

By varying the **excitatory (A), slow inhibitory (B), and fast inhibitory (G) synaptic gains**, we replicated different stages of an epileptic event, generating EEG-like signals that mimic real seizure activity.  

## Results  
Our simulations confirm that:  
1. **At the microscale**, seizure-like behavior arises from **dysfunctional ion channels**.  
2. **At the mesoscale**, seizures are driven by an imbalance in **inhibitory and excitatory synaptic activity**, particularly a **reduction in GABAergic inhibition** (B parameter).  

## Conclusion  
This study provides insights into the **biophysical mechanisms of epilepsy**, demonstrating how small changes in neuronal properties can trigger widespread seizure activity.  

## Technologies Used  
- Python (NumPy, SciPy, Matplotlib)  
- Ordinary Differential Equation (ODE) solvers  
- Hodgkin-Huxley Model  
- Wendling Model
