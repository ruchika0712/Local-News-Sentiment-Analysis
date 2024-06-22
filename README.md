# YouTube Comments Sentiment Analysis Tool

This project is a web-based application designed to scrape Social Media comments based on keywords provided, perform sentiment analysis on the collected comments, and display the sentiment analysis results in a graphical format using React for the frontend and Python for the backend.

## Features

- **Data Scraping**: Fetches comments based on user-provided keywords.
- **Sentiment Analysis**: Analyzes the sentiment of the collected comments.
- **Graphical Representation**: Displays sentiment analysis results using React-based graphs.

## Directory Structure

The project directory structure is organized as follows:

```
local-news-sentiment-analysis/
│
├── backend/
│   ├── app.py
│   ├── scraper/
│   ├── models/
│   └── ...
│
├── frontend/
│   ├── public/
│   ├── src/
│   └── ...
│
├── data/
│
├── requirements.txt
└── README.md
```

## Setup Instructions

### Backend Setup

1. Navigate to the `backend/` directory.
2. Install the required Python dependencies by running:
   ```
   pip install -r requirements.txt
   ```
3. Run the backend server:
   ```
   python app.py
   ```

### Frontend Setup

1. Navigate to the `frontend/` directory.
2. Install required Node.js dependencies by running:
   ```
   npm install
   ```
3. Start the React development server:
   ```
   npm start
   ```

## Usage

1. Access the application through a web browser.
2. Input the desired keywords to search for YouTube comments.
3. View the sentiment analysis results displayed in graphical form.
