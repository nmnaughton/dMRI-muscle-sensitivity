# dMRI in muscle sensitivity study
Repository of simulation data for paper "Global Sensitivity Analysis of Skeletal Muscle dMRI Metrics: Effects of Microstructural and Pulse Parameters" in Magnetic Resonance in Medicine. Paper may be found [here](https://doi.org/10.1002/mrm.28014).

Results for the PGSE sequence are in `sensitivity_results-PGSE.csv` and the generalized diffusion-weighted sequence (or STEAM) results are in `sensitivity_results-genDW.csv`.

To read into a multiindex pandas dataframe in python use the command: 

`df = pd.read_csv('sensitivity_results-XXXX.csv',header=[0, 1], skipinitialspace=True)`

To generate sensitivity indices, you can use the included python notebook. You will need to install the SALib package. More info @ [https://salib.readthedocs.io/en/latest/](https://salib.readthedocs.io/en/latest/). 

## Citation
If this data leads to a publication, please cite:

Naughton, NM, Georgiadis, JG. Global sensitivity analysis of skeletal muscle dMRI metrics: Effects of microstructural and pulse parameters. Magn Reson Med. 2019; 00: 1– 13. https://doi.org/10.1002/mrm.28014

```
@article{Naughton2020MRM,
author = {Naughton, Noel M. and Georgiadis, John G.},
title = {Global sensitivity analysis of skeletal muscle dMRI metrics: Effects of microstructural and pulse parameters},
journal = {Magnetic Resonance in Medicine},
volume = {83},
number = {4},
pages = {1458-1470},
doi = {10.1002/mrm.28014},
url = {https://onlinelibrary.wiley.com/doi/abs/10.1002/mrm.28014},
year = {2020}
}

```

If you have any questions about the data, please contact Noel ([nnaught2@illinois.edu](nnaught2@illinois.edu))

