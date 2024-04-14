## STYLIE
Stylistic industrial ecology (IE) model: a simple accounting tool for the energy and material service cascade 

# How to use
Starting point is a dataset on stocks and flows in the energy service cascade for either vehicles or buildings in IAMC form. Such dataset can be provided by a scenario model, such as IAMs.
Sample data in IAMC form, including the specific variable names, are provided by IAMC_Template_RECCv2.5_SampleData.xlsx.

STYLIE_ESC_Configure.xlsx configures the plots, first by selecting the right sheet in cell D4 on the Cover sheet. This way, several configurations can be defined. 
Then, by defining/listing the different plots in the 'Define ESC plot' section of the different config sheets, by defining the figure name, the type, the region, and the scenarios.
Four different types are available:
+ version_2_blds: STYLIE plot for GHG related to buildings, scope 1+2 vs. scope 3 decomposition.
+ version_3_blds: STYLIE plot for the material footprint of buildings, with decomposition.
+ version_2_pav: STYLIE plot for GHG related to vehicles, scope 1+2 decomposition.
+ version_3_pav: STYLIE plot for the material footprint of vehicles, with decomposition.

Finally, by running STYLIE_Buildings.py for buildings and STYLIE_Vehicles for vehicles.

For details on the project, see http://circomod.eu/circomod-data-hub/

# Literature
Kalt, G., Wiedenhofer, D., Görg, C., & Haberl, H. (2019). Conceptualizing energy services: A review of energy and well-being along the Energy Service Cascade. Energy Research & Social Science, 53, 47–58. https://doi.org/10.1016/j.erss.2019.02.026



