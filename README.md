# Netflix Content Analysis Project 📺

## Overview
This project analyzes Netflix's content library to uncover insights about content trends, geographic distribution, and viewing patterns. It includes a content recommendation system and various visualizations to help understand Netflix's content strategy.

## Features
- 📈 **Content Trends Analysis**: Track the growth of Netflix's library over time and analyze the impact of COVID-19 on content production
- 🌍 **Geographic Analysis**: Explore content distribution across different countries and regions
- ⏱️ **Duration Analysis**: Understand patterns in movie lengths and TV show seasons
- 📝 **Content Description Analysis**: WordCloud visualization of common themes in content descriptions
- 🎯 **Content Recommendation System**: Get personalized content recommendations based on title similarity

## Requirements
```
pandas
numpy
matplotlib
seaborn
wordcloud
scikit-learn
```

## Installation
1. Clone this repository:
```bash
git clone [repository-url]
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Download the Netflix dataset (`netflix_titles.csv`) and place it in the project root directory.

## Usage
1. Open the Jupyter notebook:
```bash
jupyter notebook netflix_analysis.ipynb
```

2. Run all cells in the notebook to generate analyses and visualizations.

3. For content recommendations, use the `get_recommendations()` function:
```python
recommendations = get_recommendations("Title of Movie or Show", df_clean)
```

## Project Structure
- `netflix_analysis.ipynb`: Main Jupyter notebook containing all analyses
- `netflix_titles.csv`: Dataset containing Netflix content information (not included)
- `requirements.txt`: List of required Python packages
- `README.md`: Project documentation

## Analysis Components
1. **Content Trends Analysis**
   - Growth of movies vs TV shows
   - Impact of COVID-19 on content production
   - Release patterns over time

2. **Geographic Analysis**
   - Top content-producing countries
   - Regional content distribution
   - Content diversity metrics

3. **Duration Analysis**
   - Movie duration distribution
   - TV show seasons distribution
   - Temporal patterns in content length

4. **Content Description Analysis**
   - Word frequency analysis
   - Common themes and keywords
   - Separate analysis for movies and TV shows

5. **Recommendation System**
   - Content-based recommendations
   - Genre matching
   - Description similarity analysis

## Data Preprocessing
The notebook includes comprehensive data preprocessing steps:
- Date parsing and formatting
- Duration extraction and standardization
- Genre and country list processing
- Missing value handling

## Visualizations
All visualizations are created using matplotlib and seaborn with:
- Clear titles and labels
- Consistent styling
- Grid lines for better readability
- Appropriate color schemes

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss the proposed changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Dataset provided by Netflix
- Inspired by various Netflix content analysis projects
- Built with Python's data science ecosystem 