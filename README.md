# DrugMechDB Analysis

This repository contains the code for analyzing the information within DrugMechDB

## Organization

The organization for this project is as follows

-  `0_data` - contains datasets either manually generated or externally acquired. Datasets without
liscencing restritions will be made availabie within the repository or downloaded as part of the
workflow.

    - `0_data/external` contains `indication_paths.yaml` from [DrugMechDB](https://github.com/SuLab/DrugMechDB)
    - `0_data/manual' contains `nodes_biolink.csv` and `edges_biolink.csv` from [MechRepoNet](https://github.com/SuLab/MechRepoNet)

-  `1_code` - Condtains the scripts used within this repository. Each is numbered in order of use

-  `2_pipeline` - Contains the output of the scripts. This directory will not be tracked via git.

## Local Location

`/gpfs/group/su/mike/DMDB_Analysis`
