# News Search Application

This application allows users to search for the latest news articles based on a query (e.g., "Pokémon") using the [NewsAPI](https://newsapi.org/). The user enters a query, and the app displays the top 3 articles, including their title, image (or a placeholder), summary, and a link to read the full article.

## Features

- **Search News**: Enter a topic (e.g., "Technology", "Sports", etc.) to fetch the latest articles related to that topic.
- **View Top 3 Articles**: Displays the 3 most recent articles along with their images (or a placeholder if no image is available), summaries, and links.
- **Responsive Interface**: Clean and simple UI with a search input, button, and results area. All components are styled for easy use.

## Prerequisites

- Python 3.x
- Required Python packages:
  - `requests`: For making HTTP requests to fetch articles from the NewsAPI.
  - `ipywidgets`: For building the interactive UI in Jupyter Notebooks.
  - `IPython`: For display functionality in Jupyter Notebooks.

## Installation

1. **Clone the repository** or download the Python file.

2. **Install dependencies** using pip:

    ```bash
    pip install requests ipywidgets
    ```

3. **Obtain a NewsAPI key**:
   - Go to [NewsAPI](https://newsapi.org/) and create an account.
   - Get your API key and replace it in the code in the variable `api_key`.

4. **Run the application**:
   - Open the Python script or Jupyter notebook and run it.
   - The app will display a search bar, and you can enter a topic to search for articles.

## Usage

- After running the app, a search bar will appear. 
- Enter a topic (e.g., "Politics", "Sports", "Technology") and click the "Search" button.
- The app will display the top 3 articles related to the query, including their title, image (or a placeholder), summary, and a link to the full article.

## Example

- **Input**: "Technology"
- **Output**: Displays 3 most recent technology-related articles with their titles, summaries, and images (if available).
