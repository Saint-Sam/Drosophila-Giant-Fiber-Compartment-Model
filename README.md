# Compartment Model for _Drosophila_ Giant Fibers

Stimulate and record from the compartments that make up the modeled Giant Fibers (GFs) of Drosophila melanogaster and study response latency and following frequency.

# Paper
This model accompanies the following paper: 
[((Frazzled/DCC regulates gap junction formation at a Drosophila giant synapse))]((https://www.biorxiv.org/content/10.1101/2025.04.08.647628v2))


It includes all code necessary to reproduce the data presented in Figure 5.

# Usage
The code was written using Jupyter Notebooks, which you can install using [Anaconda Navigator](https://www.anaconda.com/).
With this computational model,
you can study the neural activity of the _Drosophila_ GF neurons. 
The outputs of the model are figures and latencies between the onset of spikes in the first and last compartments. 

The _Drosophila_ GFs have a mixed electrochemical synapse. The chemical synapse is mediated by acetylcholine, and is represented using _gsyn_. 
The electrical synapse is defined by gap junctions passing current to the postsynaptic synapse:
- *Gap Junctions*:
A Gaussian curve defines the amount of current that can pass through the gap junction parameter _ggap_.
The x-axis of the curve ranges from 0 to 10 gap junction %, which is the proportion of gap junctions present in the axon terminal of the GFs.
The y-axis shows the current passing at any given gap junction %.

# Dependencies
All dependencies are included in the code itself.
