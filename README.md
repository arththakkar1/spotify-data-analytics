# Spotify Data Analytics Dashboard

An end-to-end data analytics project that processes raw Spotify track data and visualizes key music insights through an interactive Power BI dashboard.

## Dashboard Overview

The dashboard provides a comprehensive view of the Spotify dataset with the following KPIs and visualizations:

### Key Metrics

| Metric             | Value           |
| ------------------ | --------------- |
| Total Artists      | 3,918           |
| Total Songs        | 9,727           |
| Average Popularity | 36.53           |
| Avg Duration (min) | 3.42            |
| Most Popular Song  | i'm good (blue) |

### Visualizations

- **Top Artists** – Bar chart ranking the most prolific artists (e.g. Jack Harlow, Jhayco, Marilyn Manson, Daddy Yankee, Vybz Kartel, Feid, etc.)
- **Avg Popularity By Genre** – Horizontal bar chart comparing genres (Hard-Rock leads, followed by Chill, Acoustic, Afrobeat, Hardstyle, Goth, Pop, Alternative)
- **Total Artists By Explicit Songs** – Donut chart showing 548 (100%) explicit tracks
- **Explicit Content Scatter Plot** – Bubble chart mapping explicit vs. non-explicit song distributions
- **Artist Slicer** – Interactive filter panel for drilling down by individual artists

### Filters

- **Explicit Toggle** – Switch between `False` / `True` to filter explicit songs

## Files

| File                  | Description                                          |
| --------------------- | ---------------------------------------------------- |
| `app.ipynb`           | Jupyter notebook for data cleaning and normalization |
| `dataset.csv`         | Raw Spotify dataset (input)                          |
| `cleaned_spotify.csv` | Cleaned and processed dataset (output)               |
| `Spotify.pbix`        | Power BI dashboard file                              |
| `README.md`           | Project documentation                                |

## Data Cleaning Pipeline

1. Load and preview the raw Spotify dataset
2. Remove unnecessary columns and duplicates
3. Handle missing values and standardize text fields
4. Correct data types and split multi-artist fields
5. Convert duration to minutes and standardize genres
6. Filter out invalid records
7. Export the cleaned dataset as `cleaned_spotify.csv`

## Usage

1. Open `app.ipynb` in Jupyter or VS Code.
2. Run all cells to clean and process the data.
3. Load `cleaned_spotify.csv` into Power BI to explore the dashboard.

## Requirements

- Python 3.x
- pandas

```bash
pip install pandas
```

## Project Structure

```
spotify-data-analytics/
├── app.ipynb
├── dataset.csv
├── cleaned_spotify.csv
├── Spotify.pbix
└── README.md
```
