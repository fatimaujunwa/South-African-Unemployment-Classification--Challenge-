# South African Youth Employment Prediction Challenge
This project involves predicting the employment status of youth in the South African labour market one year after the baseline survey. The data spans four rounds of surveys conducted at 6-month intervals, containing numerical, categorical, and free-form text responses. Demographic information such as age, school level, and results is also provided.

## Challenge Overview
Data Source: Four rounds of a survey of youth in the South African labour market, conducted at 6-month intervals.
Features: Numerical, categorical, and free-form text responses, along with additional demographic information.
Objective: Predict whether a person is employed at the follow-up survey based on their baseline data.
Training Set: One row per individual, including baseline information and the target outcome (employed or not) one year later.
Test Set: Baseline data without the target outcome.

## Exploratory Data Analysis
The analysis was structured into several key sections, each aimed at exploring different aspects of the dataset to derive meaningful insights and identify potential trends or disparities.

### Geographic and Provincial Diversity
Objective: To examine regional differences in academic achievements across different geographic regions and provinces.
Approach: Grouped the dataset by geographic regions and provinces, calculating average academic scores (Matric, Degree, Diploma) for each group.
Findings: Significant disparities were observed in academic achievements across different regions and provinces, suggesting regional inequalities that may need to be addressed through targeted educational policies and interventions.
### Academic Categories
Objective: To investigate the differentiation in academic subjects across different groups.
Approach: Focused on academic variables such as Matric, Degree, and Diploma, assessing their distribution and performance across various categories.
Findings: The analysis revealed variances in academic performance, indicating the potential for detailed examination of educational outcomes across different demographics and time periods.
### Tenure's Influence
Objective: To explore the impact of tenure on academic performance.
Approach: Analyzed the relationship between tenure and academic scores, particularly focusing on Matric scores across different geographic and provincial categories.
Findings: A complex relationship was observed, with tenure not directly correlating with academic outcomes, indicating the influence of other factors on educational achievements.
Status-Based Analysis
Objective: To delve into how different statuses affect academic achievements and demographic indicators.
Approach: Grouped the dataset by status, analyzing average academic scores and demographic indicators such as gender proportion and citizenship.
Findings: Clear differences were noted across statuses in both academic outcomes and demographic compositions, highlighting the significance of status in educational and societal contexts.

## Insights and Recommendations
The analysis underscored several key insights:

Regional disparities in academic achievements necessitate targeted educational interventions.
The complex interplay between tenure and academic outcomes suggests that additional factors need to be considered to support educational achievements.
Status significantly influences academic and demographic indicators, pointing to the need for policies that address these disparities.

## Model Details
Algorithm Used: Light Gradient Boosting Machine (LGBM)
Validation Set Accuracy: 97.3%
Project Structure
data/: Contains the dataset used for training and testing.
notebooks/: Jupyter notebooks used for data exploration, feature engineering, and model training.
src/: Source code for the LGBM algorithm implementation.
models/: Saved models and model-related files.
results/: Evaluation metrics, visualizations, and insights derived from the model.
## How to Use
Clone the Repository:

Clone this repository to your local machine using the following command:
bash
Copy code
git clone https://github.com/yourusername/south-africa-youth-employment.git
Explore the Code:

Dive into the notebooks/ and src/ directories to understand the data analysis, feature engineering, and model implementation.
Reproduce Results:

Follow the steps in the Jupyter notebooks to reproduce the model training and evaluation results.

## Acknowledgments
Data provided by Predictive Insights.
The algorithm used, LGBM, demonstrated an accuracy of 97.3% on the validation set.




Here is the structured CV format with comprehensive details including your contact information, employment history, projects, skills, and education:

---

### Contact Information
- **Name:** [Your Full Name]
- **Address:** [Your Address]
- **Phone:** [Your Phone Number]
- **Email:** [Your Email Address]
- **LinkedIn:** [LinkedIn Profile URL]
- **GitHub:** [GitHub Profile URL]

### Employment History

#### Mobile App Developer
- **Company:** Surethrift Technologies LLC
- **Duration:** [Start Date] - Present
- **Responsibilities:**
  - Revitalized and published the 'Surethrift' mobile app for Cooperative Societies, boosting user engagement by 90% and reducing app crashes by 88%.
  - Enhanced user interface in collaboration with the design team, increasing user satisfaction by 98%.
  - Supported administrative and financial activities automation through the app, increasing efficiency and transparency in cooperative society management.

#### Data Analyst
- **Company:** HealthCorp Inc.
- **Duration:** [Start Date] - [End Date]
- **Responsibilities:**
  - Developed and optimized predictive models using logistic regression and random forest in Python to estimate patient medication continuation, improving model accuracy by 30%.
  - Resolved data inconsistencies within healthcare datasets, enhancing data quality and integrity which led to a 30% improvement in model accuracy and patient satisfaction.
  - Collaborated with healthcare stakeholders to translate data insights into actionable improvements in patient care, achieving 20% higher patient satisfaction and 15% improved medication adherence.
  - Utilized Power BI to present complex analytical results to interdisciplinary teams, supporting informed decision-making and enhancing team collaboration.

### Projects

#### South African Youth Employment Prediction Challenge
- **Duration:** [Start Date] - [End Date]
- **Tools Used:** Python, LGBM, Power BI
- **Repository:** [GitHub Repository](https://github.com/yourusername/south-africa-youth-employment.git)
- **Overview:** Developed a predictive model to forecast employment trends among South African youth, using survey data over four rounds to identify key employment predictors.
- **Achievements:**
  - Managed and enhanced data quality using Python, significantly improving prediction accuracy.
  - Designed features to predict employment status, contributing to a model validation accuracy of 97.3%.

#### WiDS Datathon 2024 - 1st Place Solution
- **Duration:** [Start Date] - [End Date]
- **Tools Used:** Python, Tableau, CatBoost, XGBoost
- **Repository:** [Kaggle Repository](https://www.kaggle.com/code/ujunwafatima/wids-2024-2nd-place)
- **Overview:** Secured first place by developing a predictive model for early detection of metastatic cancer.
- **Achievements:**
  - Optimized feature selection and data preprocessing using Python.
  - Implemented an ensemble strategy supported by cross-validation, achieving a CV score of 0.8025.

#### Comprehensive Data Analysis of Football Games
- **Repository:** [GitHub Project](https://github.com/fatimaujunwa/fatimaujunwa.github.io)
- **Description:** Conducted statistical analysis on football game data from the 2000s to derive insights into team performance, player statistics, and game trends.
  - Developed interactive dashboards in Tableau to highlight key trends and patterns, integrating these insights into Power BI for enhanced visualization and stakeholder reporting.

### Skills

**Technical Skills:**
- **Programming Languages:** Proficient in Python and SQL.
- **Data Analysis:** Experienced in data cleaning, preprocessing, and predictive modeling.
- **Cloud Computing:** Practical experience with AWS, Azure, and Google Cloud.
- **Business Intelligence Tools:** Advanced skills in Power BI and Tableau for creating and managing dashboards.

**Soft Skills:**
- **Problem Solving:** Strong analytical skills applied in scientific problem-solving contexts.
- **Communication:** Effective communicator with a proven ability to explain complex data to diverse audiences.
- **Adaptability:** Proven ability to adapt to new technologies and project shifts.
- **Leadership and Determination:** Demonstrated leadership in project settings; highly determined to achieve and exceed goals.

### Educational Qualification
- **Degree:** Bachelor of Science in Data Science, 2.1 Honors
- **Institution:** [Name of University]
- **Year of Graduation:** [Year]

This CV format provides a detailed yet concise overview that aligns with job-seeking best practices, emphasizing key achievements and skills relevant to potential employers in your field.
