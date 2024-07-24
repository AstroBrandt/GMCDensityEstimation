# Probablistic Model to Estimate Number Densities
This repository contains two Jupyter notebooks to showcase the model presented in Gaches 2024 (A&A submitted). To run the scripts, the following packages will be needed:
- numpy
- scipy
- astropy
- cmasher (optional, if not used, just change the colormaps in the scripts)
- multiprocess
- tqdm

  The scripts here use the example of the Taurus L1495 HGBS data. The data can be found and downloaded here http://www.herschel.fr/cea/gouldbelt/en/Phocea/Vie_des_labos/Ast/ast_visu.php?id_ast=66. You can download using
```
wget http://www.herschel.fr/Images/astImg/66/HGBS_taurus_L1495_column_density_map.fits.gz
```
and put it into a local data directly (here assumed to be `./data/` in the notebook).

For the chemical grids, unzip them into the directory and ensure that the script is pointing to them correctly.

