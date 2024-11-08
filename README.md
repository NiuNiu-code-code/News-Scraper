# News Scraper

This Python project fetches the latest news from Google News, extracts key information, and generates a word cloud based on the news titles.

## Features
1. **News Scraper**:
   - Fetches news articles from Google News RSS feed.
   - Extracts structured information including:
     - Title
     - Link
     - Date
     - Source
     - Description
   - Saves the news data to an Excel file for further analysis.

2. **Word Cloud Generator**:
   - Analyzes news titles to create a word cloud visualization.
   - Highlights the most frequently occurring words for easy comprehension.

## Installation

pip install pandas beautifulsoup4 matplotlib wordcloud



## Usage

	Run the script in the notebook


## File Structure

- News Scraper.ipynb: Main Python script for the project.
- news.xlsx: Excel file containing structured news data.
- wordcloud.png: Word cloud image generated from news titles.

## Dependencies

- Python 3
- pandas: For structured data handling and saving to Excel.
- beautifulsoup4: For parsing RSS XML data.
- matplotlib: For visualizing the word cloud.
- wordcloud: For generating the word cloud.


## Future Improvements

1. Improve description parsing for better keyword extraction.
2. Support multiple RSS feeds for broader news coverage.
3. Add sentiment analysis for each news title.

## License

This project is licensed under the MIT License.
