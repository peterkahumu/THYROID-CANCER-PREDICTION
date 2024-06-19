# Thyroid Cancer Dataset Analysis and Prediction

This repository contains the analysis and predictive modeling of thyroid cancer survival and recurrence based on patient demographics and clinical features.

## Dataset Overview
The dataset used in this project is sourced from Kaggle and focuses on thyroid disease. The data was collected over a period of 15 years, with each patient being followed for a minimum of 10 years.
[find the dataset here](https://www.kaggle.com/datasets/jainaru/thyroid-disease-data)

### Features
The dataset includes 13 clinicopathologic features which are described as follows:

- **Age**: Age of the patient at diagnosis or treatment.
- **Gender**: Gender of the patient (male or female).
- **Smoking**: Smoking status of the patient.
- **Hx Smoking**: History of smoking (if the patient has ever smoked).
- **Hx Radiotherapy**: History of receiving radiotherapy treatment.
- **Thyroid Function**: Status of thyroid function, indicating any abnormalities.
- **Physical Examination**: Findings from the physical examination, including the palpation of the thyroid gland.
- **Adenopathy**: Presence of enlarged lymph nodes in the neck region.
- **Pathology**: Specific types of thyroid cancer identified through biopsy.
- **Focality**: Whether the cancer is limited to one location (unifocal) or present in multiple locations (multifocal).
- **Risk**: Cancer risk category based on tumor size, spread, and histological type.
- **T**: Tumor classification indicating size and invasion extent.
- **N**: Nodal classification indicating lymph node involvement.
- **M**: Metastasis classification indicating distant metastases.
- **Stage**: Overall cancer stage derived from T, N, and M classifications.
- **Response**: Response to treatment (positive, negative, or stable).
- **Recurred**: Indication of cancer recurrence post-treatment.

## Objective
The primary objective of this project is to predict whether an individual is more likely to survive or succumb to thyroid cancer, given the features listed above.

## Data Source
The data for this project is procured from the UCI Machine Learning Repository's thyroid disease datasets.

## Analysis and Modeling
The analysis involves exploratory data analysis (EDA) to understand the underlying patterns in the dataset, followed by the development of predictive models to estimate survival and recurrence outcomes.

## Usage
To run the analysis and predictive models, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/peterkahumu/THYROID-DATASET-PREDICTION-AND-EXPLORATORY-DATA-ANALYSIS.git
    ```
2. Navigate to the project directory:
    ```sh
    cd thyroid-cancer-analysis
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```
4. Run the Jupyter notebooks for exploratory data analysis and predictive modeling.

## Contributions
Contributions are welcome! If you have suggestions or improvements, please create an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements
I acknowledge the Kaggle for providing the dataset used in this analysis.
You can view the dataset [here](https://www.kaggle.com/datasets/jainaru/thyroid-disease-data)
Thank you for viewing the notebook.
