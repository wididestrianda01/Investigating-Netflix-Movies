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
├── ANALYSIS_SUMMARY.md      # Comprehensive analysis findings and methodology
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
   cd "Investigating Netflix Movies"
   ```

2. **Create and activate environment**
   ```bash
   # Using conda (recommended)
   conda env create -f environment.yml
   conda activate netflix-analysis

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

- **Movie Duration Distribution**: 1990s movies show a characteristic distribution pattern with most films falling within standard theatrical release durations, ranging from short films to extended epics
- **Genre Diversity**: Drama and Comedy appear to be well-represented, with the decade showcasing a rich tapestry of cinematic genres that provide excellent material for nostalgic content production
- **Geographic Representation**: Strong international representation including robust US presence and evidence of global cinema distribution on Netflix
- **Technical Excellence**: The analysis demonstrates comprehensive data science methodology with professional visualizations, statistical rigor, and well-documented code
- **Business Insights**: Data-driven insights for nostalgic content production planning, including duration targeting and genre selection guidance

For detailed findings and methodology, see [ANALYSIS_SUMMARY.md](ANALYSIS_SUMMARY.md).

## Technologies Used

- **Python 3.9**: Primary programming language
- **Pandas**: Data manipulation and analysis (≥1.3.0)
- **Matplotlib**: Data visualization and plotting (≥3.4.0)
- **Jupyter Notebooks**: Interactive analysis environment

## Contributing

This project was developed as part of a DataCamp analysis project. Feel free to:
- Explore the data with your own questions
- Suggest additional visualizations
- Improve the analysis methodology
- Add new insights or findings

## Data Source

The Netflix dataset contains information about movies and TV shows available on the Netflix platform. This project focuses specifically on the movie subset, with particular attention to films released during the 1990s decade for nostalgic analysis purposes.

## License

This project is for educational and research purposes. The Netflix dataset is used for analytical insights and learning objectives as part of a DataCamp project.
