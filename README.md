# Investigating Netflix Movies from the 1990s

A comprehensive data analysis project exploring Netflix movie data with a focus on films released during the 1990s decade. This project analyzes movie duration patterns and provides insights into the nostalgic entertainment era.

## Project Overview

This project examines Netflix movie data to uncover interesting patterns and trends specifically for movies released in the 1990s. As a production company specializing in nostalgic styles, this analysis helps understand the characteristics of this awesome movie decade through exploratory data analysis.

## Dataset

The project uses the Netflix dataset (`data/raw/netflix_data.csv`) which contains comprehensive information about:
- **4,812 Netflix titles** including movies and TV shows
- **Movie details**: Title, director, cast, country of origin
- **Release information**: Release year, date added to Netflix
- **Content metadata**: Duration, genre, description
- **Geographic data**: Country of production

## Key Analysis Areas

- **1990s Movie Focus**: Filtering and analyzing movies specifically from 1990-1999
- **Duration Analysis**: Distribution patterns of movie lengths in the nostalgic decade
- **Genre Exploration**: Understanding the types of movies popular in the 1990s
- **Temporal Patterns**: How 1990s movies were added to Netflix over time
- **Content Characteristics**: Analyzing descriptions and themes of 90s cinema

## Project Structure

```
Investigating Netflix Movies/
├── data/                    # Data storage and documentation
│   ├── raw/                 # Original Netflix dataset
│   │   └── netflix_data.csv # Complete Netflix dataset with movies and shows
│   └── README.md            # Data documentation
├── notebooks/               # Jupyter notebooks for analysis
│   ├── notebook.ipynb       # Main analysis notebook
│   ├── redpopcorn.jpg       # Project header image
│   └── archive/             # Archived notebook versions
├── environment.yml          # Conda environment specification
├── requirements.txt         # Python dependencies
├── setup.py                # Package configuration
└── README.md               # This file
```

## Getting Started

### Prerequisites
- Python 3.7+
- Conda or pip for package management

### Installation

1. **Clone the repository** (if applicable)
   ```bash
   git clone <repository-url>
   cd "Visualizing the History of Nobel Prize Winners"
   ```

2. **Create and activate environment**
   ```bash
   # Using conda (recommended)
   conda env create -f environment.yml
   conda activate nobel-analysis

   # Or using pip
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open the main analysis notebook**
   - Navigate to `notebooks/notebook.ipynb`
   - Run all cells to reproduce the analysis

## Key Findings

The analysis reveals several interesting insights about 1990s Netflix movies:

- **Movie Duration Distribution**: 1990s movies show a characteristic distribution pattern with most films falling within typical feature-length ranges
- **Genre Diversity**: The decade featured a rich variety of genres from dramas to comedies
- **Geographic Representation**: Movies from various countries, with strong representation from the United States and international cinema
- **Nostalgic Content**: The dataset provides excellent material for understanding the entertainment preferences of the nostalgic 1990s era
- **Netflix Curation**: Insights into how Netflix has curated and added classic 1990s content to their platform over time

## Technologies Used

- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **Matplotlib/Seaborn**: Data visualization
- **Jupyter Notebooks**: Interactive analysis environment
- **NumPy**: Numerical computations

## Contributing

This project was developed as part of a DataCamp analysis project. Feel free to:
- Explore the data with your own questions
- Suggest additional visualizations
- Improve the analysis methodology
- Add new insights or findings

## Data Source

The Netflix dataset contains information about movies and TV shows available on the Netflix platform. This project focuses specifically on the movie subset, with particular attention to films released during the 1990s decade for nostalgic analysis purposes.

## License

This project is for educational and research purposes. The Nobel Prize data is publicly available, and visualizations are created for analytical insights.
