# project

This repository was created as part of Module 6 of the UBC MDS Data Science Toolbox course, and demonstrates good practices for file naming, project organization, and reproducible computational environments.

## Contents

- data/ - raw dataset files
- docs/ - supporting documents, including meeting minutes and reference materials
- images/ - image files used in the project
- src/ - Python scripts, run in order (01_generate-data.py, 02_visualize-data.py, 03_plot-predictions.py)
- reports/ - the analysis notebook (Report.ipynb)
- environment.yaml - Conda environment specification for reproducing the computational environment
- LICENSE - project license
- .gitignore - excludes log files, .DS_Store, and Jupyter checkpoint files from version control

## Setup

To recreate the environment used for this project, run:

conda env create -f environment.yaml
conda activate project-env
