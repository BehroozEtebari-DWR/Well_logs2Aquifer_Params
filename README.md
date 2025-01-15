# Well_logs2Aquifer_Params
# Well Completion Reports and Airborne Electromagnetic (AEM) Surveys' Coarse Fractions to Aquifer Hydraulic Properties : 
# Avg Coarse Fraction, Avg_Kxy, Avg_Kv, Avg_Ss, Avg_Sy
California Well completion reports(Well Logs) to Texture and Aquifer Parameters Python codes


These Python codes generate Unified Soil Classification System (USCS) designations for well completion reports from the California Department of Water Resources' (DWR) Online System for Well Completion Reports (OSWCR) 
available at: 
https://data.ca.gov/dataset/well-completion-reports


AEM Coarse Fractions and
Ramboll well completion reports digitized as Supporting files for AEM flight lines at: 
https://data.cnra.ca.gov/dataset/aem

SVSim Texture datasets:  
https://data.cnra.ca.gov/dataset/svsim


For the following inputs, you will need to run the code separately for each input file. This means that for each individual input file, you should execute the code independently, ensuring that each file is processed one at a time. Make sure to modify the file path or input settings in the code before each run, depending on the specific file being used.


# Pre-Processing Aquifer Parameters for C2VSimFG v2.0 (IWFM Engine) Model with 4 Layers Using ArcPy (IDW; No Pilot Points)

This repository includes tools for pre-processing aquifer parameters from scratch to model nodes for the C2VSimFG version 2.0 model (IWFM Engine) with 4 layers. The workflow utilizes ArcPy for interpolation (IDW) and does not rely on pilot points.

### Additional Jupyter Notebooks

Three Python Jupyter Notebooks (`10.0`, `10.1`, and `10.3`) have been developed to facilitate the conversion of pre-processed aquifer parameters, including the following:

- `Avg_CoarseFraction`
- `Avg_Kxy`
- `Avg_Kv`
- `Avg_Ss`
- `Avg_Sy`

These parameters are processed for all four layers of the C2VSimFG v2.0 model.

### References

- **IWFM Engine:** [Integrated Water Flow Model (IWFM)](https://data.ca.gov/dataset/integrated-water-flow-model-iwfm)  
- **C2VSimFG Version 1.5:** California Central Valley Groundwater-Surface Water Simulation Model – Fine Grid (C2VSimFG)[C2VSimFG Dataset](https://data.cnra.ca.gov/dataset/c2vsimfg)  

### Customizing for Other Model Configurations

For models with additional layers (e.g., 5, 6, 10, or 20), you may need to update the input IWFM model node file name and file path accordingly. Alternatively, you can convert GIS node shapefiles to CSV files as required.

### Need Help?

Feel free to reach out if you need assistance with adjusting the code or require specific instructions for processing multiple files!
