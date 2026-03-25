# NBA_heatmap

This project uses Python to analyze NBA player shot data and generate visualizations including shot charts and shot efficiency maps.

I am currently in the process of learning and developing my python skills, and wanted to work on pulling data with visualizations. 

It includes:
- Shot location visualization (makes vs misses)
- Shot efficiency mapping using hexbin plots
- Data retrieval via NBA API
- Clean, modular Python code structure

---

## Features

-  Retrieve player data dynamically
-  Generate shot charts (scatter plots)
-  Create shot efficiency maps (hexbin visualization)
-  Modular functions for reusability
-  Custom basketball court overlay

---

## What I used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- nba_api

---

##  How It Works

1. User inputs:
   - Player name
   - Season

2. The program:
   - Finds the player ID using NBA API
   - Retrieves shot data
   - Processes the data into a DataFrame

3. Outputs:
   - Shot chart (makes vs misses)
   - Shot efficiency map (FG% by location)

---

## Future Improvements
Add interactive dashboard (Streamlit)
Compare multiple players
Add filtering by shot zone or game situation
Improve visual styling (NBA-style charts)

Created by Rick A.
