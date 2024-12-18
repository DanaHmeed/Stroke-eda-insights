# Stroke-eda-insights

### Overview
According to the World Health Organization (WHO), stroke is the second leading cause of death globally, accounting for approximately 11% of total deaths. This project analyzes a dataset containing demographic, health, and lifestyle information to understand factors associated with stroke occurrence. 

### Objective
The main goals of this project are:
1. To perform exploratory data analysis (EDA) and derive statistical insights about stroke-related factors.
2. To understand patterns and relationships within the dataset.
3. To create a Power BI dashboard for visualizing key insights.

### Dataset
The dataset (`stroke.csv`) contains the following columns:
- `id`: Unique identifier for each individual.
- `gender`: Gender of the individual.
- `age`: Age of the individual.
- `hypertension`: Whether the individual has hypertension (1 = Yes, 0 = No).
- `heart_disease`: Whether the individual has heart disease (1 = Yes, 0 = No).
- `ever_married`: Marital status.
- `work_type`: Type of work the individual is engaged in.
- `Residence_type`: Type of residence (Urban/Rural).
- `avg_glucose_level`: Average glucose level in the blood.
- `bmi`: Body Mass Index (BMI).
- `smoking_status`: Smoking habits (e.g., Never smoked, Formerly smoked).
- `stroke`: Whether the individual experienced a stroke (1 = Yes, 0 = No).

### Technologies Used
- **Python**: For data analysis and visualization.
  - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Power BI**: For creating interactive dashboards.

### Project Structure
```plaintext
stroke-data-analysis/
|-- stroke.csv                   # Dataset file
|-- exploratory_analysis.ipynb   # Jupyter Notebook for EDA
|-- PowerBI_Dashboard.pbix       # Power BI dashboard file
|-- README.md                    # Project documentation
```

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stroke-data-analysis.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the `exploratory_analysis.ipynb` file in Jupyter Notebook or JupyterLab.

### Analysis Steps
1. **Data Cleaning**:
   - Handle missing values.
   - Ensure proper data types for each column.
2. **Exploratory Data Analysis (EDA)**:
   - Analyze distributions, correlations, and key features associated with strokes.
   - Use visualizations like histograms, box plots, and heatmaps.
3. **Insights and Visualization**:
   - Identify significant trends and patterns.
   - Use Power BI to create an interactive dashboard.

### Dashboard Features
The Power BI dashboard provides insights such as:
- Distribution of stroke cases across different demographics.
- Impact of health conditions like hypertension and heart disease on stroke occurrence.
- Trends in glucose levels, BMI, and other health metrics.

### Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Feature description"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Acknowledgements
- World Health Organization (WHO) for highlighting the significance of stroke-related research.
- The contributors and maintainers of Python libraries used in this project.

---
