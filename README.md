# bioenergetic_modeling
This repository is the modeling archive in support of a River Corridor SFA publication "Thermodynamic control on the decomposition of organic matter across different electron acceptors" (Zheng et al., Soil Biology and Biochemistry.  2024. https://doi.org/10.1016/j.soilbio.2024.109364

In this research, a thermodynamic modeling framework is built to flexibly incorporate both organic matter (OM) molecules and electron acceptors for estimating potential free energy release from various redox reactions and to further predict reaction rates based on Microbial Transition State Theory. The model package includes scripts for thermodynamic modeling and postprocessing. Input Fourier-transform ion cyclotron resonance (FTICR) data are from a previous experimental study (Boye et al., 2018), and model outputs are free energy predictions and stoichiometric coefficients associated with all possible redox reactions.

![image](https://github.com/river-corridors-sfa/MM_bioenergetic_modeling/assets/16612176/29e34119-044f-4c44-a983-a2d765454b3e)

Model: scripts to calculate free energy change of reactions and energy efficiency across different electron acceptors

Input_FTICR: FTICR based organic matter composition data, used as input of bioenergetic models (see Boye et al., 2018 Discerning microbially mediated processes during redox transitions in flooded soils using carbon and energy balances)

Model_output: model output files and sensitivity analysis. All files were named after "soil"+"treatment" ("1" for controls)

Output_processing: cybernetic modeling and graphing scripts

