# Bias-Detection-and-Mitigation-in-Ride-Hailing

## Overview
This project examines potential socioeconomic and demographic biases in ride-hailing pricing algorithms, with a focus on identifying and addressing fare disparities that disproportionately affect marginalized communities. Leveraging New York City Taxi and Limousine Commission (TLC) data, the study analyzes ride patterns, pricing structures, and service accessibility to uncover systemic inequities in fare allocation. By integrating advanced analytical methods and fairness-aware machine learning models, the research aims to reconcile predictive accuracy with equitable pricing outcomes. Preliminary findings reveal correlations between fare discrepancies and factors such as neighborhood income levels, racial demographics, and geographic isolation, particularly in underserved areas. The project proposes algorithmic adjustments, including fairness constraints and transparency-enhancing frameworks, to mitigate biases without compromising service efficiency. These insights advocate for policy and platform reforms to ensure ride-hailing systems prioritize both profitability and social equity, fostering inclusive urban mobility solutions that serve all communities equitably.

## Requirements
Packages: Python 3.6+, `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`. 

## Setup Instructions
Build and Run Locally
If you'd like to run the project directly on your local machine:

Clone the Repository Clone this repository to your local machine using the following command:

git clone https://github.com/gracejiang0929/FA24_DSC180A_Repo.git
cd FA24_DSC180A_Repo
Create a Virtual Environment (Optional but Recommended):

python -m venv venv
Activate the Virtual Environment:
On macOS/Linux:
source venv/bin/activate
On Windows:
venv\Scripts\activate
Install Dependencies:

pip install -r requirements.txt
Launch Jupyter Notebook:

jupyter notebook
Open the Notebook: In the Jupyter interface, navigate to final_notebook.ipynb and open it.

Run the Notebook: Execute the cells sequentially to perform bias mitigation analysis.

Data Setup
The file h181.csv is required to run the project but is too large to include in the repository.

You can download the file from [https://drive.google.com/file/d/1GESPjTTEgwczg4AJVGqvzLJsFhBZky7f/view?usp=drive_link] and place it in the data/raw/ directory.

IMPORTANT In order to run Section 3. Model Development without Debiasing, you need to follow below steps:

--- 

1. Clone the Repository
   Clone this repository to your local machine using the following command: 
   
   ```bash
   git clone https://github.com/gracejiang0929/FA24_DSC180A_Repo.git
   cd FA24_DSC180A_Repo

2. Create a Virtual Environment (Optional but Recommended):
   ```bash
   python -m venv venv
   
- Activate the Virtual Environment:
   - On macOS/Linux:
     ```bash
     source venv/bin/activate

   - On Windows:
     ```bash
     venv\Scripts\activate

3. Install Dependencies:
   ```bash
   pip install -r requirements.txt

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook

5. Open the Notebook:
   In the Jupyter interface, navigate to `final_notebook.ipynb` and open it.

6. Run the Notebook:
   Execute the cells sequentially to perform bias mitigation analysis.
