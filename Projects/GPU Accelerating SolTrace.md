
Speed up Monte Carlo ray tracing simulations for solar thermal power applications using GPU computing.

Problem: Monte Carlo simulations of the optical system that makes up a CSP plant takes ~ten million rays to converge. 

Solution: Upgrade SolTrace to use GPUs because modern work station GPUs can handle ~ten thousand rays at the same time, while CPUs can handle ~ten rays at the same time.
## Images
[Luning Bakke](https://github.com/LuningFang) made this graph showing how much faster the GPU is. She wrote a lot of Optix stuff in the [repo](https://github.com/NLR-SolTrace/SolTrace).
![GUI example](https://github.com/nickmedwards/ESOL_wiki/blob/main/images/Projects/GPU_Accerating_SolTrace/speedup_graph.png?raw=true)

[Nicholas Brunhart-Lupo](https://github.com/nicholasbl), who on the project, is making a nice looking GUI!
![GUI example](https://github.com/nickmedwards/ESOL_wiki/blob/main/images/Projects/GPU_Accerating_SolTrace/gui_example.png?raw=true)

# Stuff Used
[[Windows PowerShell]], [[git]], [[Visual Studio]], [[Visual Studio Code]], [[cpp]], [[python]]
