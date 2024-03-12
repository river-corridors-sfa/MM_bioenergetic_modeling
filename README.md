# bioenergetic_modeling
This repository is the modeling archive in support of a River Corridor SFA publication "Thermodynamic control on the decomposition of organic matter across different electron acceptors" (Zheng et al., Soil Biology and Biochemistry.  2024. https://doi.org/10.1016/j.soilbio.2024.109364

In this research, a thermodynamic modeling framework is built to flexibly incorporate both organic matter (OM) molecules and electron acceptors for estimating potential free energy release from various redox reactions and to further predict reaction rates based on Microbial Transition State Theory. The model package includes scripts for thermodynamic modeling and postprocessing. Input Fourier-transform ion cyclotron resonance (FTICR) data are from a previous experimental study (Boye et al., 2018), and model outputs are free energy predictions and stoichiometric coefficients associated with all possible redox reactions.

![Figure 1](https://github.com/river-corridors-sfa/MM_bioenergetic_modeling/assets/16612176/4b231acc-a19b-408e-ae23-ab496843f780)

Model: Scripts for defining and running thermodynamic calculations using Fourier-transform ion cyclotron resonance mass spectrometry (FTICR-MS) based organic matter characterization as electron donors and different electron acceptors. Briefly, from FTICR-MS identified and assigned chemical formula of OM, the free energy of OM oxidation is estimated from nominal oxidation state of carbon (NOSC). Meanwhile, both catabolic and anabolic reactions can be obtained using the general formula of OM (C_a H_b N_c O_d P_e S_f^z). Energy coupling leads to the stoichiometry of metabolic reaction. Refer to the manuscript associated with this data package for more details.

Input_FTICR: FTICR based organic matter composition data, used as input of bioenergetic models (see Boye et al., 2018 Discerning microbially mediated processes during redox transitions in flooded soils using carbon and energy balances)

Outputs: The outputs folder contains all the stoichiometric information from model simulations. The output-processing folder contains scripts for reaction rate calculations based on Microbial Transition State Theory, which relates the growth rate to the amount of energy available to perform cellular work.




