# dMRI-muscle-sensitivity
Repository of simulation data for paper "Global Sensitivity Analysis of Skeletal Muscle dMRI Metrics: Effects of Microstructural and Pulse Parameters" in Magnetic Resonance in Medicine. Paper may be found [here](https://doi.org/10.1002/mrm.28014).

Results for the PGSE sequence are in `sensitivity_results-PGSE.csv` and the generalized diffusion-weighted sequence (or STEAM) results are in `sensitivity_results-genDW.csv`.

To read into a multiindex dataframe in python use the command: 

`df = pd.read_csv('sensitivity_results-XXXX.csv',header=[0, 1], skipinitialspace=True)`

To generate sensitivity indices, you can use the included python notebook. You will need to install the SALib package. More info @ [https://salib.readthedocs.io/en/latest/](https://salib.readthedocs.io/en/latest/). 

## Citation
If this data leads to a publication, please cite:

`Naughton, NM, Georgiadis, JG. Global sensitivity analysis of skeletal muscle dMRI metrics: Effects of microstructural and pulse parameters. Magn Reson Med. 2019; 00: 1– 13. https://doi.org/10.1002/mrm.28014`

If you have any questions about the data, please contact Noel ([nnaught2@illinois.edu](nnaught2@illinois.edu))

