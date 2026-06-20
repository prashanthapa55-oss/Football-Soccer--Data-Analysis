# Football Data Analysis — A Decade of FIFA Player Data (FIFA 15-24)

## Overview
I've played FIFA my whole life, so I wanted to dig into the real data behind it — 
does a player's rating actually predict their market value, or do other factors matter more?

This project analyzes 157,768+ player records across 10 years of FIFA/EA Sports FC 
(2015-2024) to explore how player value, rating, and position relate to each other.

## Tools Used
Python (Pandas), SQL (SQLite), Matplotlib, Seaborn, Jupyter Notebook

## Key Questions
1. Which leagues produce the highest-rated players?
2. Which positions are over/undervalued relative to their rating?
3. What attributes most influence overall rating?
4. Which clubs get the best value for money?
5. How has player value evolved across FIFA versions?

## Key Findings
- **Attacking positions are overvalued**: CF, LW, and RW players have much higher 
  market values than their ratings alone would suggest, while fullbacks are undervalued.
- **Technical skill beats speed**: Passing (0.71 correlation) and dribbling (0.66) 
  predict overall rating far more than pace (0.18).
- **Market inflation outpaces skill growth**: Average player value nearly tripled 
  (€1.09M → €2.96M) from 2015-2024, while average rating barely moved (63.9 → 66.0).
- **Top leagues**: La Liga, Premier League, and Serie A lead in average rating, 
  though the gap to lower-ranked leagues is smaller than expected.

## Files
- `football-data-anaylsis.ipynb` — full analysis notebook
- `value_vs_rating.png`, `position_value.png`, `league_rating.png` — visualizations

## Data Source
[EA Sports FC 24 Complete Player Dataset](https://www.kaggle.com/datasets/stefanoleone992/ea-sports-fc-24-complete-player-dataset) (Kaggle)
