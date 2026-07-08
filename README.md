# Bollywood Analysis

Exploratory data analysis of Bollywood filmography using the IMDb API. Tracks how prolific India's top actors have been across their careers, year by year.

## What it does

- Scrapes filmography data for 35+ Bollywood actors via the `imdbpy` library
- Counts movies per year per actor
- Generates bar charts of career output over time
- Exports per-actor filmography to CSV (Shah Rukh Khan included)

## Files

| File | Purpose |
|---|---|
| `IMDB.py` | Interactive tool — enter any actor name, get their career timeline chart |
| `Analysis.py` | Batch analysis across all 35+ actors, spike detection |
| `Shah Rukh Khan_filmography_df.csv` | Sample output dataset |

## Actors covered

Aamir Khan, Shah Rukh Khan, Amitabh Bachchan, Salman Khan, Hrithik Roshan, Rajinikanth, Irrfan Khan, and 30+ more.

## Stack

Python · `imdbpy` · `pandas` · `matplotlib` · `numpy`

## Running

```bash
pip install imdbpy pandas matplotlib numpy
python IMDB.py        # interactive: enter any actor name
python Analysis.py    # batch analysis across all actors
```
