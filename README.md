# GloBox A/B Test Analysis

This repository contains the analysis and findings from the **GloBox A/B Test Analysis**, focused on evaluating the impact of a new banner on GloBox's mobile e-commerce platform. The project leverages A/B testing methodologies to assess user engagement and spending behavior, providing data-driven recommendations for business decisions.

## Project Overview

The project aims to evaluate whether introducing a banner for the food and drink category improves user conversion rates and average spending without negatively impacting user experience. Key aspects of the experiment include:

- **Platform:** Mobile website
- **Test Duration:** 13 days (25th January - 6th February 2023)
- **Metrics Analyzed:**
  - Conversion Rate (CR)
  - Average Amount Spent (AAS)
- **Tools Used:**
  - SQL
  - Tableau
  - Spreadsheets
  - Statistical analysis methods (z-tests, t-tests)

## Key Findings

1. **Conversion Rate (CR):**
   - Significant improvement: Increased from 3.92% (control group) to 4.63% (treatment group).
   - Statistical significance: p < 0.001 with an effect size (Cohen's h) of 3.86.

2. **Average Amount Spent (AAS):**
   - Minor, statistically insignificant increase: $3.37 (control group) to $3.39 (treatment group).
   - p-value = 0.943.

3. **Demographic and Regional Insights:**
   - Positive CR impact across genders.
   - Varying effects on AAS by country and gender.
   - Stable AAS suggests a shift towards frequent, lower-priced purchases.

4. **No Novelty Effect:**
   - Sustained improvement in CR, even after the initial days of the experiment.

5. **Power Analysis:**
   - Recommended durations: 24 days for CR and 152 days for AAS to detect a 10% minimum detectable effect (MDE).

## Recommendations

1. **Launch the Banner:** 
   - Data supports a positive impact on CR with no adverse effects on AAS.
   - Expected to drive long-term user engagement and revenue growth.

2. **Continuous Monitoring:**
   - Assess the banner's performance across different demographics, devices, and regions.
   - Monitor for any unforeseen negative impacts on key metrics.

3. **Extended Observation:**
   - Re-run the experiment for the recommended durations to solidify conclusions.

## Repository Structure

- `Presentation.pdf`: A concise summary of the project and key insights.
- `Report.pdf`: Detailed analysis, methodology, and findings.
- `AB_Test_Recommendations.pdf`: Business recommendations derived from the study.
- `Working_Notes.pdf`: Notes on SQL queries, methodology, and thought processes.
- `Tableau_Workbook.twbx`: visualizations of the results.
- `Datasets/`: Contains raw and processed datasets used in the analysis.

## How to Use

1. Explore the detailed findings in the `Report.pdf`.
2. View visualizations using Tableau and the provided `.twbx` file.
3. Run the SQL queries in `Working_Notes.pdf` to replicate data preparation steps.

## Contact

For questions or collaboration opportunities, please reach out to:
**Christopher H. Kroll: ChristopherHKroll@gmail.com**

---

This project exemplifies the use of A/B testing and data analytics to make informed decisions in e-commerce. Your feedback and contributions are welcome!
