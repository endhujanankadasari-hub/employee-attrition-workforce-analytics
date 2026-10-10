# Employee Attrition & Workforce Analytics using Python

A Google Colab-based exploratory data analysis project using the **IBM HR Analytics Employee Attrition & Performance** dataset.

## Repository structure

```text
Employee_Attrition_Workforce_Analytics/
├── 01_Data_Understanding/
│   └── README.md
├── 02_Data_Cleaning/
│   └── README.md
├── 03_Exploratory_Data_Analysis/
│   └── README.md
├── 04_Attrition_Analysis/
│   └── README.md
├── 05_Visualizations/
│   └── README.md
├── 06_Business_Insights/
│   └── README.md
├── 07_Reports_and_Presentation/
│   └── README.md
├── outputs/
│   └── README.md
├── Employee_Attrition_Workforce_Analytics.ipynb
├── README.md
└── requirements.txt
```

## Dataset

IBM HR Analytics Employee Attrition & Performance  
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

Review the Kaggle dataset terms before redistributing the raw CSV. Linking to the source is a good default.

## Business questions

- What is the overall attrition rate?
- Which departments and job roles have higher attrition rates?
- Is overtime associated with attrition?
- How do monthly income, job satisfaction, distance from home, age, and work-life balance compare between employees who leave and stay?
- What differences are observed by tenure and other workforce characteristics?

## EDA requirements covered

- Dataset shape, types, descriptive statistics, and data dictionary
- Missing-value, duplicate, invalid-value, and constant-column checks
- Categorical and numerical analysis
- Group-by summaries and attrition-based comparisons
- Histograms, box plots, bar charts, count plots, and scatter plots
- Correlation heatmap and IQR-based outlier diagnostics
- Business insights, recommendations, and limitations
- PDF report and 7-slide PowerPoint generated from the actual data

**Time series:** The supplied dataset has no suitable event-date field for monthly attrition trends. The notebook documents this rather than fabricating a chart.

## Run in Google Colab

1. Download this repository ZIP and extract it, or upload the notebook to Google Drive.
2. Open `Employee_Attrition_Workforce_Analytics.ipynb` in [Google Colab](https://colab.research.google.com/).
3. Run all cells from top to bottom.
4. The notebook attempts to retrieve the dataset. If that fails, follow the notebook prompt to upload the CSV downloaded from Kaggle.
5. Check that every cell finishes without errors and review the charts and generated findings.
6. The final notebook cell generates `outputs/EDA_Report.pdf` and `outputs/Presentation.pptx`, plus figures and CSV summaries.
7. Download the generated deliverables and add them to the repository before final submission.

## Final verification checklist

- [ ] Restart runtime and run all cells from top to bottom.
- [ ] Check that the loaded dataset is the intended IBM HR CSV.
- [ ] Verify the attrition rate and group summaries against notebook output.
- [ ] Confirm visualizations display correctly.
- [ ] Open the generated PDF and PowerPoint.
- [ ] Upload the final PDF, PPTX, notebook, README, and relevant outputs to GitHub.

## Interpretation and limitations

This is observational EDA. Associations do not prove causality. Interpret attrition rates with group sizes and job context. Do not use these descriptive results alone to make individual employment decisions.
