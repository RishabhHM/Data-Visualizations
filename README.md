# U.S. Patent Distribution Analysis (2000-2015)

A comprehensive data visualization project analyzing the geographic distribution and growth patterns of patent activity across U.S. Metropolitan Statistical Areas from 2000 to 2015.

## 🔗 Live Demo

**View the Interactive Report:** [https://rishabhhm.github.io/Data-Visualizations/](https://rishabhhm.github.io/Data-Visualizations/)

## 📊 Project Overview

This project examines utility patent grants across 380+ Metropolitan Statistical Areas (MSAs) in the United States, identifying innovation hubs and regional growth trends over a 15-year period. The analysis reveals significant geographic concentration in coastal technology corridors alongside emerging innovation centers in unexpected regions.

## 📁 Repository Structure
```
├── index.html                              # Main visualization webpage report
├── Patent Distribution Across MSA.twbx     # Tableau workbook with interactive dashboards
├── research.ipynb                          # Data processing and analysis notebook
└── README.md                               # Project documentation
```

## 🗂️ File Descriptions

### `index.html`
The primary deliverable - a comprehensive visualization report featuring:
- Interactive Tableau dashboard embed with choropleth maps
- Top 5 MSAs by patent count and growth rate
- Regional trend analysis (278 words)
- Complete methodology and data sources
- **[View Live →](https://rishabhhm.github.io/Data-Visualizations/)**

### `Patent Distribution Across MSA.twbx`
Tableau workbook containing:
- **2015 Patent Distribution** map - Choropleth visualization of absolute patent counts
- **Patent Expansion 2000→2015** map - Growth rate visualization with diverging color scheme
- **Overview Dashboard** - Combined analytics with filters for Top 5 highlighting
- Interactive filters and tooltips for detailed exploration

### `research.ipynb`
Jupyter notebook documenting:
- Data collection via web scraping from USPTO website
- Data understanding and exploratory analysis
- Processing and cleaning of patent data
- CBSA shapefile integration
- Growth rate calculations and rankings
- Data export for Tableau visualization

## 🛠️ Technologies Used

- **Data Collection:** Python (BeautifulSoup, requests, pandas)
- **Data Processing:** Python (pandas, geopandas)
- **Visualization:** Tableau Public
- **Web Development:** HTML5, CSS3
- **Geographic Data:** U.S. Census Bureau TIGER/Line Shapefiles

## 📊 Data Sources

- **Patent Data:** U.S. Patent and Trademark Office (USPTO) Technology Assessment and Forecast (TAF) Database
  - Source: [USPTO CBSA Patent Data](https://www.uspto.gov/web/offices/ac/ido/oeip/taf/cls_cbsa/allcbsa_gd.htm)
  - Coverage: Utility patents granted 2000-2015
  - Classification: By first-named inventor residence

- **Geographic Data:** U.S. Census Bureau 2015 TIGER/Line Shapefiles
  - Source: [Census Bureau CBSA Shapefiles](https://www2.census.gov/geo/tiger/TIGER2015/CBSA/)
  - Type: Core Based Statistical Areas (CBSAs)
  - Focus: Metropolitan Statistical Areas only

## 🚀 How to Use

### View the Report
Simply visit: [https://rishabhhm.github.io/Data-Visualizations/](https://rishabhhm.github.io/Data-Visualizations/)

### Run Locally
1. Clone the repository:
```bash
   git clone https://github.com/rishabhhm/Data-Visualizations.git
   cd Data-Visualizations
```

2. Open `index.html` in your web browser

### Explore Tableau Workbook
1. Download `Patent Distribution Across MSA.twbx`
2. Open with Tableau Desktop or Tableau Public

### Run Analysis Notebook
1. Install required packages:
```bash
   pip install pandas geopandas requests beautifulsoup4 jupyter
```
2. Open `research.ipynb` in Jupyter:
```bash
   jupyter notebook research.ipynb
```

## 📄 License

This project is created for academic/research purposes. 
- Patent data: Public domain (USPTO)
- Geographic data: Public domain (U.S. Census Bureau)
- Original analysis and visualizations: [Your License Choice]

## 👤 Author

**Rishabh**
- GitHub: [@rishabhhm](https://github.com/rishabhhm)
- Project Link: [https://github.com/rishabhhm/Data-Visualizations](https://github.com/rishabhhm/Data-Visualizations)

## 🙏 Acknowledgments

- U.S. Patent and Trademark Office for patent data
- U.S. Census Bureau for geographic shapefiles
- Tableau Public for visualization platform
- GitHub Pages for hosting

---

**Last Updated:** December 2025
