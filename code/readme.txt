1. Spatial attribution analysis.ipynb

Method: Based on the XGBoost machine learning algorithm and SHAP (SHapley Additive exPlanations) framework

Function: Conducts spatial attribution analysis of the ALAN-DFS relationship


2. PCMCI+.ipynb

Method: Uses the PCMCI+ algorithm while controlling for climatic variables (temperature, precipitation, solar radiation)

Function: Computes causal relationships and their strengths between:

(1) ALAN and DFS

(2) ALAN and mediating variables (LUE, WUE, SIF, Vcmax)

(3) Mediating variables and DFS


3. DFS models.ipynb

Method: Phenology model optimization

Function:

(1) Determines the optimal parameter combinations and performance for four base phenology models (CDD, DM, SIAM, DMT)

(2) Evaluates the improved models incorporating ALAN (CDD-ALAN, DM-ALAN, SIAM-ALAN, DMT-ALAN) in terms of optimal parameters and performance

The required data can be found in the 'input-data' folder.