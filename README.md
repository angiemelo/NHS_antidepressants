# NHS Antidepressants Prescribing Analysis

## Project Overview
This project focuses on analysing trends in antidepressant prescribing in the UK, with a detailed breakdown of prescribing volumes and costs. The dataset explores national and regional patterns, monthly trends and the drivers behind fluctuations in prescription items and associated costs for individual drugs. By studying these trends, the analysis aims to provide insights into healthcare prescribing practices, drug pricing dynamics and potential impacts on healthcare expenditure.

## Key Features
- **Annual Trends Analysis**: Examine overall prescribing volume and cost trends across multiple years.
- **Monthly Trends Analysis**: Visualize longitudinal monthly trends for items prescribed and costs for antidepressants.
- **Drug-Specific Insights**: Identify top-prescribed drugs and explore their influence on monthly prescribing trends.
- **Cost vs. Volume Comparison**: Investigate discrepancies between the number of items prescribed and their associated costs.
- **Percentage Contribution**: Calculate the percentage contribution of specific drugs to total volume and cost for each month.

## Technologies Used
- **Python**: Core programming language for analysis.
- **Pandas**: Used for data cleaning, aggregation, and manipulation.
- **Seaborn & Matplotlib**: Visualization libraries for creating clear and impactful graphs.
- **Jupyter Notebook**: For interactive coding and analysis.

## Data Description
The dataset (`pca_regional_drug_summary_df`) contains the following columns:
- **YEAR_MONTH**: Monthly time periods.
- **REGION_NAME**: Geographical region within the UK.
- **BNF_CHEMICAL_SUBSTANCE**: Name of the drug prescribed.
- **COST**: Total cost associated with the drug prescriptions.
- **ITEMS**: Number of prescription items dispensed.

## Steps of Analysis
1. **Data Preparation**: Clean the dataset, filter for relevant drugs (e.g., Sertraline hydrochloride), and group data by time periods and drugs.
2. **Annual Analysis**: Identify trends and anomalies in yearly prescribing costs and volume.
3. **Monthly Analysis**:
   - Aggregate data by `YEAR_MONTH` and drug.
   - Visualize prescribing trends using line plots and bar charts.
4. **Drug-Specific Analysis**: Compare the top-prescribed drugs (e.g., Sertraline, Citalopram) and their costs and volumes.
5. **Percentage Contribution Calculation**:
   - Calculate the percentage volume and cost for each drug relative to monthly totals.
6. **Findings**: Highlight key discrepancies, such as cost reductions or spikes, independent of prescribing volume.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/angiemelo/NHS_antidepressants.git
   cd NHS_antidepressants
   ```
2. Install dependencies:
   ```bash
   pip install pandas seaborn matplotlib
   ```
3. Open the analysis script or Jupyter Notebook in your favorite editor.
4. Ensure the dataset (`pca_regional_drug_summary_df`) is loaded correctly.
5. Run the analysis and generate visualizations.

## Key Findings
- **Sertraline hydrochloride**: Consistently the most prescribed drug, with cost reductions driving overall prescription expenditure decreases in 2022.
- **Citalopram**: Notable spike in costs in July 2022, more than doubling before returning to normal levels. This fluctuation occurred despite consistent prescription volumes.
- **Discrepancies**: The cost and volume trends generally align but show anomalies in certain months where cost changes are independent of volume fluctuations.

## Future Steps
- Investigate external factors influencing prescribing practices (e.g., policy changes or supply chain issues).
- Integrate advanced modeling techniques for seasonality and trend analysis.
- Expand the analysis to include additional drug classes and regions.

## Contact
For questions or feedback, please reach me at angiemelox@gmail.com
