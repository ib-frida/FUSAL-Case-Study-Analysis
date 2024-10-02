# FUSAL Case Study Analysis

This repository contains data analysis, visualizations, and insights for the FUSAL project, which is part of the **Social Innovation diploma** at the **University for Peace (UPEACE)**. The project was conducted as a requirement for the **Monitoring & Evaluation Fundamentals: Measuring Outcomes & Impact** course, focusing on evaluating malnutrition patterns across different communities and measuring outcomes to assess the impact of interventions.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data](#data)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Results and Insights](#results-and-insights)
6. [Contributing](#contributing)
7. [License](#license)

## Project Overview

The **FUSAL Case Study** is a core part of the **Social Innovation diploma** at **UPEACE** under the **Monitoring & Evaluation Fundamentals: Measuring Outcomes & Impact** course. It focuses on evaluating malnutrition rates across different regions in El Salvador, analyzing key trends and developing evidence-based insights. The project aims to:

- Detect patterns of malnutrition across specific communities.
- Identify unexpected trends and anomalies.
- Propose actionable recommendations based on data-driven insights.

The analysis was performed using Python and various libraries to process, visualize, and analyze the data.

## Data

The dataset contains records of malnutrition rates from several communities, including Guaymango, Chiltiupan, and Apaneca, covering the period from 2014 to 2017. The data is used to examine longitudinal trends and identify any significant changes over time.

### Data Files:
1. **malnutrition_data.csv**: The main dataset containing malnutrition rates across multiple communities from 2014 to 2017.
2. **image1.png, image2.png, image3.png**: Visual representations of malnutrition trends generated through the analysis.
3. **analysis_notebook.ipynb**: A Jupyter notebook with detailed analysis, code, and visualizations.

## Installation

To run the analysis locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/fusal-case-study.git
   cd fusal-case-study
   ```

2. **Set up a virtual environment (optional but recommended)**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Jupyter Notebook
All analysis is performed in the `analysis_notebook.ipynb`. To run it:

1. Launch the notebook:
   ```bash
   jupyter notebook analysis_notebook.ipynb
   ```

2. The notebook includes:
   - Data loading and preparation steps.
   - Exploratory Data Analysis (EDA) to examine malnutrition trends.
   - Visualizations for longitudinal and community-specific trends.
   - Actionable recommendations based on the findings.

### Script Execution

If you prefer running the analysis via script, you can execute:
```bash
python analysis_script.py
```
This will generate and display the results of the malnutrition data analysis. Modify the script if you wish to explore different communities or analysis parameters.

## Results and Insights

Key findings from the analysis include:
- **Guaymango** shows persistently high malnutrition rates with little improvement.
- **Chiltiupan** presents significant fluctuations, with only temporary improvements between 2014 and 2017.
- **Apaneca** and **Ataco** show continuous declines in malnutrition rates, likely due to successful interventions.
  
Further insights and recommendations for future action are detailed in the `analysis_notebook.ipynb`.

### Sample Visualization
![Sample Graph](image1.png)

### Recommendations
Based on the analysis:
- Further investigation into the interventions in **Guaymango** and **Chiltiupan** is recommended.
- Replication of successful strategies from **Apaneca** and **Ataco** to other communities may help improve malnutrition rates.


## License

This project is licensed under the MIT License. Please refer to the `LICENSE` file for further details.
