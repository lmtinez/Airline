# Customer Loyalty Analysis and Prediction

## Overview
This project focuses on analyzing customer loyalty data and predicting customer behavior using machine learning. The dataset contains information about customer loyalty history and flight activity. The objective is to derive insights and develop predictive models to support business strategies in enhancing customer retention.

## Project Structure
The repository contains the following files:

- `Customer Loyalty History.csv`: Historical customer loyalty data.
- `Customer Flight Activity.csv`: Customer flight activity data, including flight frequency and loyalty points.
- `analysis_script.py`: Python script used for data analysis and machine learning modeling.
- `presentation.pptx`: Presentation summarizing the project's findings and methodology.

All files are located in the root directory of the repository.

## Data Description
### Customer Loyalty History
This dataset includes customer details such as:
- Membership IDs.
- Historical loyalty scores.
- Retention status.

### Customer Flight Activity
This dataset contains information about:
- Flight frequency in different years.
- Loyalty points earned.

## Methodology
1. Data Cleaning: Processed missing values and inconsistencies.
2. Feature Engineering: Generated features from the datasets to support predictive modeling.
3. Machine Learning: Built models using logistic regression and random forest algorithms.
4. Evaluation: Assessed model performance using metrics such as accuracy and precision.

## How to Use
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your_username/your_repository.git
   cd your_repository
   ```
2. Install dependencies:
   Make sure to have Python installed along with the required libraries (e.g., `pandas`, `numpy`, `sklearn`, `matplotlib`). Install them using:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis script:
Execute the analysis script in the `src/` directory:
   ```bash
   python src/analysis_script.py
   ```
4. Review the presentation:
Open the PowerPoint file in the `presentation/` directory to see the project summary.

## Results
- Key Insights:
    - Identified patterns in customer loyalty and retention.
    - Clustered customer behaviors based on flight activity.
- Model Performance:
    - Random Forest model achieved a high precision of ~80-90%.

## Author
Laura Martínez Bueno

https://www.linkedin.com/in/lmtinezbueno/

Feel free to reach out for collaboration or feedback!
