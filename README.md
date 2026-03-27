# Spotify Data Analytics

This project provides a comprehensive workflow for cleaning and preparing Spotify track data for analytics using Python and pandas.

## Features

- Loads and previews raw Spotify dataset
- Cleans and normalizes data for analysis:
  - Removes unnecessary columns and duplicates
  - Handles missing values and standardizes text fields
  - Corrects data types and splits multi-artist fields
  - Converts duration to minutes and standardizes genres
  - Filters out invalid records
- Exports the cleaned dataset for further analysis or visualization

## Files

- `app.ipynb`: Jupyter notebook containing the step-by-step data cleaning and normalization process with explanations for each step.
- `dataset.csv`: Raw Spotify dataset (input)
- `cleaned_spotify.csv`: Cleaned and processed dataset (output)

## Usage

1. Open `app.ipynb` in Jupyter or VS Code.
2. Run each cell in order to clean and process the data.
3. The cleaned data will be saved as `cleaned_spotify.csv` in the project directory.

## Requirements

- Python 3.x
- pandas

Install dependencies with:

```bash
pip install pandas
```

## Project Structure

```
spotify-data-analytics/
├── app.ipynb
├── dataset.csv
├── cleaned_spotify.csv
└── README.md
```

## License

This project is for educational and analytical purposes.
