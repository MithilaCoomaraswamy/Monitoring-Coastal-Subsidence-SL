
# Monitoring Coastal Subsidence in Sri Lanka

This repository contains a suite of Python scripts designed to monitor land-surface deformation in coastal lagoons of Sri Lanka: Rekawa, Jaffna, Batticaloa and Chilaw. Utilizing Sentinel-1 Synthetic Aperture Radar (SAR) data, this project identifies millimeter-scale subsidence trends critical for assessing urban stability and climate change vulnerability in the study areas.

## Methodology

This notebook utilises the PyGMTSAR ecosystem to transform stacks of Sentinel-1 Synthetic Aperture Radar (SAR) imagery into actionable geodetic data on subsidence.

This pipeline implements a hybrid SBAS-PS approach. By integrating Persistent Scatterer (PS) interferometry, we pinpoint stable urban reflectors to achieve millimeter-scale accuracy on infrastructure, while the Small BAseline Subset (SBAS) technique ensures broad-scale coverage over Sri Lanka's dynamic coastal and wetland landscapes.

## Credits & Attribution

The PyGMTSAR InSAR library, Geomed3D Geophysical Inversion Library, N-Cube 3D/4D GIS Data Visualization, among others used in this notebook, are open-source projects developed by **Alexey Pechnikov**. 

The original script can be found at:  
[Google Colab Original Script](https://colab.research.google.com/drive/1ipiQGbvUF8duzjZER8v-_R48DSpSmgvQ?usp=sharing)

### Support the Developer
You can support Alexey Pechnikov's work on [Patreon](https://www.patreon.com/pechnikov), where he shares updates on his projects, publications, use cases, examples, and other useful information. For research and development services and support, please visit his profile on the freelance platform [Upwork](https://www.upwork.com).

© Alexey Pechnikov, 2024
