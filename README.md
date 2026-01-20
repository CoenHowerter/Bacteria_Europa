# Bacteria_Europa

This project is a numerical model exploring the potential habitability of Europa (Jupiter’s moon) for microbial life. The model evaluates how radiation, temperature, ice thickness, and internal heating interact to influence microbial growth potential at the surface and subsurface.

The goal is not to claim life can exist on Europa, but to test how environmental parameters affect biological viability when nutrients is provided.

The project is organized as a Jupyter Lab notebook, divided into:

Baseline
  └── Growth under Earth-like reference conditions

Europa
  ├── Surface
  │     ├── Conditions
  │     ├── Simulation
  │     └── Plotting (latitude to day/night)
  │
  ├── Subsurface
  │     ├── Conditions
  │     ├── Simulation
  │     └── Plotting (depth profiles from surface to ocean)
  │
  └── Parameter Sensitivity
        ├── Radiation sweep
        ├── Ice thickness sweep
        ├── Geothermal heating sweep
        └── Plotting (each sweep to growth)
