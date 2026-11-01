# Steam Game Rating Prediction

Final-year ML portfolio project predicting Steam game review ratings from metadata.

## Dataset
Steam Dataset 2025 (Zenodo DOI: 10.5281/zenodo.17286923, CC BY 4.0).
Download from Kaggle: https://www.kaggle.com/datasets/artermiloff/steam-games-dataset
*Note: Data is not committed to this repo due to size and licence restrictions.*

## Project Structure
- `notebooks/` — Jupyter notebooks (contains the data audit, preprocessing, and baseline model)
- `src/` — reusable Python functions (if needed)
- `data/` — download instructions (data not committed)
- `requirements.txt` — required packages

## Setup Instructions

1. Clone the repository:
   `git clone https://github.com/callyam1/steam-rating-prediction.git`
2. Create a virtual environment:
   `python3 -m venv .venv`
3. Activate the environment:
   `source .venv/bin/activate`
4. Install required packages:
   `pip install -r requirements.txt`

## How to Run
1. Download the dataset from the Kaggle link above.
2. Place the `applications.csv`, `review_labels.csv`, `application_genres.csv`, and `genres.csv` files into a `data/` folder in the root of the project.
3. Open the notebook: `notebooks/Milestone2_Data_and_Baseline.ipynb`.
4. Run all cells from top to bottom.