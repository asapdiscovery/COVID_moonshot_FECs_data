[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8215553.svg)](https://doi.org/10.5281/zenodo.8215553)

# COVID_moonshot_FECs_data

Collection of free energy calculation data run on [FoldingAtHome](https://foldingathome.org/?lng=en) during the COVID Moonshot. 

Contents:
- `moonshot_pred_vs_measured_DG.ipynb` : notebook to generate all files in this repository. This involves downloading from a collection of AWS S3 URLs and plotting/statistics of predictions versus experimental measures.
- `paths_to_fah_aws_landings.txt` : paths to retrieved F@H Moonshot sprint dashboards hosted on AWS.
- `fecs_predictions_with_expt.csv` : Free energy predictions with experimental measures to compare against (n=1341).
- `fecs_predictions_all.csv` : All retrieved free energy predictions done on F@H during Moonshot (n=22518).
 - `./structures/` : tarballs of retrieved docked ligands and Mpro structures used for free energy simulations.
