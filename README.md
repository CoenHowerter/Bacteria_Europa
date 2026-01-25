<!DOCTYPE html>
<html lang="en">
</head>

<body>

<h1>Europa Bacteria Habitability Model</h1>

<p>
This repository contains a numerical research model exploring the potential
habitability of Europa, one of Jupiter’s icy moons, for microbial life.
The project investigates how environmental factors such as radiation,
temperature, ice thickness, and internal heating influence microbial growth
potential at and below the surface.
</p>

<div class="note">
This project does not claim that life exists on Europa.
It is an exploratory, parameter based model designed to examine how known
physical conditions might affect biological viability under hypothetical
nutrient availability.
</div>

<hr>

<h2>Goals</h2>

<ul>
  <li>Model microbial growth response to Europa-like environmental conditions</li>
  <li>Compare Europa conditions against an Earth-like baseline</li>
  <li>Explore sensitivity to radiation, ice thickness, and geothermal heating</li>
  <li>Visualize surface and subsurface habitability trends</li>
</ul>

<hr>

<h2>Structure</h2>

<pre>
Baseline
  └── Growth under Earth-like reference conditions

Europa
  ├── Surface
  │     ├── Environmental conditions
  │     ├── Growth simulation
  │     └── Plotting (latitude, day/night effects)
  │
  ├── Subsurface
  │     ├── Environmental conditions
  │     ├── Growth simulation
  │     └── Plotting (depth profiles from surface to ocean)
  │
  └── Parameter Sensitivity
        ├── Radiation sweep
        ├── Ice thickness sweep
        ├── Geothermal heating sweep
        └── Growth response visualization
</pre>

<hr>

<h2>Implementation</h2>

<p>
The model is implemented as a Jupyter Notebook
<code>GrowthEuropa.ipynb</code>, which contains:
</p>

<ul>
  <li>Physical parameter definitions</li>
  <li>Growth-rate calculations</li>
  <li>Surface and subsurface simulations</li>
  <li>Visualization of results</li>
</ul>

<p>
The notebook is structured to allow parameters to be modified easily for
experimentation and sensitivity analysis.
</p>

<hr>

<h2>Assumptions & Limitations</h2>

<ul>
  <li>Nutrient availability is assumed and not explicitly modeled</li>
  <li>Biological behavior is simplified and parameterized</li>
  <li>The model is not intended for predictive or observational claims</li>
  <li>Results are qualitative and exploratory in nature</li>
</ul>

<hr>

<h2>Intended Use</h2>

<p>
This repository is intended for:
</p>

<ul>
  <li>Academic exploration and learning</li>
  <li>Astrobiology and planetary science modeling practice</li>
  <li>Parameter sensitivity experiments</li>
  <li>Early-stage research or concept development</li>
</ul>

<hr>

<h2>Status</h2>

<p>
This project is <strong>unpublished</strong> and under active development.
Structure, assumptions, and results may change as the model evolves.
</p>

</body>
</html>
