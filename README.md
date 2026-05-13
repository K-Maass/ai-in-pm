# AI in PM

## Setup

```bash
pip install -r requirements.txt
```

## Running the notebooks

Run the notebooks from the repository root so relative data paths resolve:

```bash
jupyter notebook
```

Execute the coding notebooks in this order:

1. `notebooks/Exercise_3_Data_Preparation_and_EDA.ipynb`
2. `notebooks/Exercise_4_Feature_Engineering_&_Feature_Extraction.ipynb`
3. `notebooks/Exercise_5_Direct_Constrained_Rule_Search.ipynb`
4. `notebooks/Exercise_7_Improved_Classification.ipynb`
5. `notebooks/Exercise_9_The_Summer_Swell.ipynb`

Presentation assets are in `powerpoints/`, including:

- `powerpoints/AI in Production Management Project.pptx`
- `powerpoints/Graphs.ipynb`

The submitted notebooks are self-contained. They standardize notebook-facing
labels to `0 = BAD` and `1 = GOOD` while preserving raw CSV labels as
`Manual_Label_Raw`, and downstream notebooks read only the explicit outputs
created by earlier notebooks in the sequence.

The key generated artifacts are included under `outputs/`:

- `outputs/exercise3_master_table_case_level.csv`
- `outputs/exercise4_engineered_features.csv`
- `outputs/exercise5_plc_predictions.csv`
- `outputs/exercise5_plc_search_results.csv`
- `outputs/logbook_events_structured.csv`
- `outputs/exercise7_model_artifact.joblib`
- `outputs/exercise7_model_comparison.csv`
- `outputs/exercise7_feature_importance.csv`
- `outputs/exercise9_heatwave_predictions.csv`
- `outputs/exercise9_drift_audit.csv`
- `outputs/exercise9_good_case_drift_audit.csv`

Exercise 7 uses repository-relative paths and does not depend on a local user
directory.
