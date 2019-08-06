# dMRI-muscle-sensitivity
Repository of data from paper "Global Sensitivity Analysis of Skeletal Muscle dMRI Metrics: Effects of Microstructural and PGSE Pulse Parameters" submitted to Magnetic Resonance in Medicine.

Results for the PGSE sequence are in 'sensitivity_results-PGSE.csv' and the generalized diffusion-weighted sequence (or STEAM) results are in 'sensitivity_results-genDW.csv'.

To read into a multiindex dataframe in python use the command: 

`df = pd.read_csv('sensitivity_results-XXXX.csv',header=[0, 1], skipinitialspace=True)`

To generate sensitivity indices, you can use the included python notebook. You will need to install the SALib package. More info @ [https://salib.readthedocs.io/en/latest/](https://salib.readthedocs.io/en/latest/). 

