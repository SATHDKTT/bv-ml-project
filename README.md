
# Gemstone Classifier
**Authors** Stephan Amann, Tanja Huber, David Kleindiek

**Date** 15.03.2024

GitHub repository for the final project of the 'Machine Learning and Image Processing ' class during the winter term at the Eberhard-Karls Universität Tübingen.

The project report is available [here](doc/Gemstone_Classifier.pdf)

## Overview
This repository contains the research work conducted to develop a gemstone classifier using machine learning techniques. The aim of this project is to accurately classify different types of gemstones based on their visual features, aiding in the identification process.

## Objectives
 - Scrape gemstone images from online sources to create a diverse and representative dataset.
 - Preprocess the collected data, including resizing images, handling missing values, and encoding categorical variables, to prepare it for training a machine learning model.
 - Train a machine learning model on the prepared dataset and evaluate its performance using appropriate metrics to assess accuracy and reliability.

## Repository Structure

The repository is organized into several directories:

 - [`src/`](src): Contains Python scripts for data scraping, preprocessing, model training, and evaluation.
 - [`mod/`](mod): Contains trained model files, including the results of each epoch during training for each dataset. 
 - [`dat/`](dat): Contains raw and processed data files used in the project, including images of gemstones, metadata, and intermediate datasets.
 - [`doc/`](doc): Documentation, including the project report and any additional figures.

```css
Users need to obtain the model files and datasets themselves due to their large file sizes.
```
### Running the code
1. Clone the repository:
```bash
git clone https://github.com/SATHDKTT/bv-ml-project.git
cd bv-ml-project
```
2. Set Up a Virtual Environment (Optional but Recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
3. Install Required Packages:
```bash
pip install -r requirements.txt
```
4. Run The Notebooks:
```bash
jupyter notebook src/
```
