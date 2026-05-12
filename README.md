# AI in PM

## Setup

```bash
pip install -r requirements.txt
```

## Running the notebooks

Run the notebooks from the repository root so the relative data paths resolve:

```bash
jupyter notebook
```

The final notebook set is:

- `notebooks/Exercise_3_Data_Preparation_and_EDA.ipynb`
- `notebooks/Exercise_4_Feature_Engineering_&_Feature_Extraction.ipynb`
- `notebooks/Exercise_5_Direct_Constrained_Rule_Search.ipynb`
- `notebooks/Exercise_7_Improved_Classification.ipynb`
- `notebooks/Exercise_9_The_Summer_Swell.ipynb`

Presentation assets are in `powerpoints/`, including:

- `powerpoints/AI in Production Management Project.pptx`
- `powerpoints/Graphs.ipynb`

The key generated CSVs required by Exercise 5 and Exercise 7 are included under
`outputs/`:

- `outputs/exercise3_master_table_case_level.csv`
- `outputs/exercise5_plc_predictions.csv`
- `outputs/logbook_events_structured.csv`

Exercise 7 uses repository-relative paths and does not depend on a local user
directory.
