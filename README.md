# ALK-electrolyzer-model_UNIFI
Main repository for a physics-based, parametric model of an alkaline (ALK) water electrolyzer cell developed by the University of Florence (Italy).
This repository provides a lightweight Python implementation to generate ALK cell performance curves and efficiency trends as a function of operating conditions. The model combines standard electrochemical relationships (reversible voltage, activation losses, ohmic losses) with literature-based correlations and a temperature-dependent Faraday efficiency fit. References are embedded directly in the source code as DOI links in the comments.

---

## What is included

- **Physics-based ALK cell model (ElectroCellALK)**

	- Polarization curve generation (current density range up to rated value)

	- Reversible voltage in standard conditions plus Nernst correction (pressure and vapor terms)

	- Activation overpotentials via Tafel formulation (anode and cathode)

	- Ohmic losses including electrode contributions and an empirical resistance term

	- Faraday efficiency correlation with optional temperature-dependent coefficient interpolation

	- Thermal model



## Design updates and contributions

Design updates are welcome via Pull Requests or by contacting the authors. When contributing, it is recommended to:

- document new correlations and assumptions in code comments (with DOI/reference),

- include a minimal test or example that reproduces expected trends.

## Citation

If this model is used in research or publications, please cite the associated technical report or software record (to be added). If no report is available yet, consider citing the repository itself (release tag and commit hash) and the primary sources referenced in the code comments.


## Author contacts 
- Alessandro Bianchini: 	alessandro.bianchini@unifi.it
- Francesco Superchi: 	francesco.superchi@unifi.it


