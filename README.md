![image](assets/Logo.png)

# MicroSpot Reader

Web-App for the detection of bioactive features in an untargeted metabolomics experiment with concomitant bioactivity determination.

## Web-App

The Web-App is based on streamlit and currently runs on the streamlit cloud service:

[![Open Website!](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://uspotreader.streamlit.app/)

### Local Installation:

MicrospotReader can be installed on Windows and Linux. For installation on Linux please download the `linux` branch of this repository.

1. Clone this repository
2. Open Windows Terminal and go to the main folder of the repository:

`cd <filepath>`

1. Create and activate a new conda environment:

`conda env create -f environment.yml`

`conda activate uspotreader`

4. Start the App by running `run.py`


## Jupyter Notebooks

Additionally, this Repository contains Jupyter Notebooks in the `notebooks`-folder if you do not wish to use the Web-App:

- `image_analysis.ipynb`: Detection and analysis of MicroSpots as well as antimicrobial halos within an image. Determination of bioactivity.

- `data_preparation.ipynb`: Concatenation of Spot-Lists of the same LC-MS run and correlation of MicroSpots with a retention time.

- `feature_finding.ipynb`: Feature detection and annotation with activity data from .csv file prepared with previous steps and a .mzML file.