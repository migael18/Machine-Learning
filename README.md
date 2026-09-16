# Mental Health in Tech: Unsupervised Learning

## Project overview
This project analyses the OSMI Mental Health in Tech Survey 2016,
containing 1,433 respondents and 63 variables. It explores whether
clustering can identify groups relevant to an HR mental-health
support programme.

## Analysis
The notebook includes:
- Data exploration and missing-value assessment.
- Initial encoding of the full dataset.
- A six-feature model using median imputation.
- Age correction and a revised four-feature model.
- K-Means and Ward hierarchical clustering.
- Elbow and silhouette evaluation.
- PCA visualisation and cluster profiles.

## Main findings
The final exploratory K-Means solution uses four clusters and
achieves a silhouette score of 0.5248. Four clusters were selected
for interpretability; nine clusters had the highest tested score.

The groups mainly reflect employment circumstances and
treatment-seeking history. They do not establish distinct
mental-health support needs.

## Files
The `Final Project Machine Learning` folder contains:
- `projectmachine.ipynb`: analysis notebook and saved outputs.
- `final_clusters_pca.png`: final cluster visualisation.
- `final_elbow_silhouette.png`: final model evaluation.
- `refined_elbow_silhouette.png`: earlier six-feature evaluation.
- The report in PDF and editable Word formats.

## Dataset
OSMI Mental Health in Tech Survey 2016:
https://www.kaggle.com/osmi/mental-health-in-tech-2016

The raw dataset must be obtained separately.

## Running the notebook
1. Install Python and Jupyter Notebook or use VS Code with
   its Python and Jupyter extensions.
2. Install the required packages:
   `python -m pip install pandas numpy scikit-learn matplotlib`
3. Download the dataset.
4. Update the CSV path in the notebook to its location on
   your computer.
5. Run the notebook cells in order.
