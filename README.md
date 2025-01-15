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


# Pre-Processing Aquier Parameters starting from scratch to model nodes for C2VSimFG version 2.0(IWFM Engine) model 4 layers using ArcPy (IDW; no pilot points)
There are three additonal python Jupyter Notebooks (10.0 & 10.1 and 10.3) developed to convert aformentioned data into Aquifer Parameters:
parameters = ['Avg_CoarseFraction', 'Avg_Kxy', 'Avg_Kv', 'Avg_Ss', 'Avg_Sy']  for all four C2VsimFG2.0 layers, 
IWFM Engine : https://data.ca.gov/dataset/integrated-water-flow-model-iwfm
C2VSimFG version 1.5 : https://data.cnra.ca.gov/dataset/c2vsimfg
for another model nodes with additional layers( like 5,6,10,20) you may need to change the input IWFM model node file name and path (or convert gis node shapefile to csv file)

Let me know if you need help adjusting the code or if you would like more specific instructions for running the code for multiple files!
