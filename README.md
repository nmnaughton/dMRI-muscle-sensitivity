# dMRI-muscle-sensitivity
Repository of data form paper "Global Sensitivity Analysis of Skeletal Muscle dMRI Metrics: Effects of Microstructural and PGSE Pulse Parameters" submitted to Magnetic Resonance in Medicine.

Results are in 'sensitivity_results.csv'

To read in to python use the command: 

`df = pd.read_csv('sensitivity_results.csv',header=[0, 1], skipinitialspace=True)`

To generate sensitiivty indices, you can use the included python notebook. You will need to install the SALib package. More info @ [https://salib.readthedocs.io/en/latest/](https://salib.readthedocs.io/en/latest/). 

