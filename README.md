![matlab version: R2019a](https://img.shields.io/badge/Matlab-R2019a-red)
![R version: 4.2.0](https://img.shields.io/badge/R-4.2.0-red)
[![DOI](https://zenodo.org/badge/502868293.svg)](https://zenodo.org/badge/latestdoi/502868293)



# SubMIC_Carvacrol

**SubMIC_Carvacrol:** A predictive microbiology framework to determine the effect of **Sub**inhibitory concentrations (working under the **M**inimal **I**nhibitory **C**oncentration) of **Carvacrol** on the foodborne bacterial species *Escherichia coli* and *Bacillus cereus*.

**Simulations:**
The code in the repository provides experimental data and (model-based) estimated parameters to simulate the inactivation dynamics of *Escherichia coli* and *Bacillus cereus* viable counts (log scale of CFUs/mL) under different subinhibitory concentrations of **Carvarol** (mg/mL) during a time-lapse of 48 hours. The code integrates the mathematical model introduced in the article (soon-to-come) to explain the experimental data. The estimation of the model parameters to fit the data was performed using the **MATLAB** optimization toolbox **AMIGO2**, freely available at: https://sites.google.com/site/amigo2toolbox .

Two codes are provided in the repository: the one titled *Carvacrol_Inhibition_of_Ecoli_Bcereus-Model&Data.m*, to be run in the commercial computing software **MATLAB**, and the other named *Carvacrol_Inhibition_of_Ecoli_Bcereus-Model&Data.R*, to be run in the free software for statistical computing **R**. The code has been kept simple so that the user can introduce different parameter values and/or experimental data to simulate the model.

**Parameter_Estimation:**
The code in the repository provides the necessary files to perform the estimation of model parameters using the **MATLAB** optimization toolbox **AMIGO2**:
**- Run_PE.m:** Main file to run parameter estimation using **AMIGO2**.
**- Model_SubMIC_Carvacrol.m:** File to generate the mathematical model in **AMIGO2** standard.
**- PostProcess.m:** File to plot estimation results and postprocessing data.
**- Plot_ExpData.m:** File to plot experimental data.


**Structural_Identifiability:**
**- z_create_Model_SubMIC_Carvacrol:** 
**- options.m:**
**- Model_SubMIC_Carvacrol.mat:**


