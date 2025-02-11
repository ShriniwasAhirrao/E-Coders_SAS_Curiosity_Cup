# E-Coders SAS Curiosity Cup Project

This repository contains the work for the **E-Coders SAS Curiosity Cup** project, which involves data cleaning, exploratory analysis, model training, and visualization for research and analysis. Below is an outline of the file structure and how to get familiar with this project.

## File Structure

```plaintext
├── .gitignore                  # Specifies files and directories to ignore in the repository.
├── LICENSE                     # License for the project.
├── README.md                   # This readme file.
├── requirements.txt            # List of Python dependencies required for the project.
├── Work_Log

├── datasets
|   |── Merged_data
|   |   └── Merged_dataset      # merged overall dataset and affected by disaster vs GDP dataset
│   ├── Cleaned_data            # Cleaned data used for analysis.
│   │   └── Clean_Data_info.txt # Description of the cleaned data.
│   ├── external_sources        # Data sourced from external APIs.
│   │   └── external_API_info.txt # Information about the external APIs used.
│   └── Raw_data                # Raw data used for the project.
│       ├── 1424986_file_Quantifying_Vulnerability_DB.xls
│       ├── affected-by-disasters-vs-gdp.csv
│       └── ...                 # Other raw data files.
├── notebooks
│   ├── Data_cleaning           # Jupyter notebooks for data cleaning.
│   │   └── data_cleaning_notebook.txt # Documentation of data cleaning process.
│   └── exploratory_analysis    # Jupyter notebooks for exploratory data analysis.
│       └── Exploratory_analysis_notebook.txt # Documentation of exploratory analysis.
├── reports
│   ├── presentation.pptx       # Presentation slides.
│   ├── Research Finding.txt    # Document summarizing research findings.
│   └── Research Paper          # Folder containing the research paper.
│       └── research_paper.txt  # Text of the research paper.
├── results
│   ├── model_outputs           # Folder containing model output results.
│   │   └── model_output.txt    # Output of the trained model.
│   └── visualizations          # Folder containing visualizations of results.
│       └── visualizations.txt  # Description of visualizations.
├── SAS
│   ├── analysis.sas            # SAS script for analysis.
│   ├── data_cleaning.sas       # SAS script for data cleaning.
│   └── visualization.sas       # SAS script for visualizations.
└── scripts
    ├── data_preprocessing.py   # Python script for data preprocessing.
    ├── feature_engineering.py  # Python script for feature engineering.
    └── model_training.py       # Python script for model training.
```

## Getting Started

### Prerequisites
To get started with this project, you need to have the following installed:

- **Python 3.x** (for running Python scripts and notebooks)
- **SAS** (for running the SAS-specific scripts in the `SAS` folder)
- **Jupyter Notebook** (for running notebooks in the `notebooks` folder)

#### Required Python Libraries
Install them by running:

```bash
pip install -r requirements.txt
```

## File Descriptions

- **`datasets/`**: Contains all the datasets used for the project, including raw data, external sources, and cleaned data.
- **`notebooks/`**: Contains Jupyter notebooks for data cleaning and exploratory analysis. You can open these notebooks using Jupyter Notebook or JupyterLab.
- **`reports/`**: Contains the research paper, presentation slides, and findings document.
- **`results/`**: Contains the model outputs and visualizations.
- **`SAS/`**: Contains SAS scripts for analysis, data cleaning, and visualization.
- **`scripts/`**: Python scripts for data preprocessing, feature engineering, and model training.

## Usage

### Data Cleaning
First, check the data cleaning notebook or SAS scripts in the `notebooks/Data_cleaning/` or `SAS/data_cleaning.sas` for instructions on how the data is cleaned.

### Exploratory Analysis
Use the `notebooks/exploratory_analysis/` or `SAS/visualization.sas` to explore and analyze the datasets.

### Training the Model
Use the Python script in `scripts/model_training.py` to train the model. The script will preprocess data, train the model, and output the results in `results/model_outputs/`.

### Visualizations
Visualize the results using the `notebooks/exploratory_analysis/` or `SAS/visualization.sas`. Visualizations are stored in the `results/visualizations/` folder.

## How to Contribute

1. **Fork** the repository.
2. **Clone** your fork to your local machine.
3. **Create a new branch**:
   ```bash
   git checkout -b your-branch-name
   ```
4. **Make your changes** and commit them:
   ```bash
   git commit -am 'Your message'
   ```
5. **Push to your branch**:
   ```bash
   git push origin your-branch-name
   ```
6. **Create a pull request**.

## License
This project is licensed under the MIT License.

## Conclusion
This repository contains all the materials for the **E-Coders SAS Curiosity Cup** project. Explore the folders for data, analysis scripts, notebooks, and reports to understand the work done, and feel free to contribute if you'd like to collaborate.
