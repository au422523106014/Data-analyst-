# Sentiment Analysis of Political Speeches

This project analyzes sentiment shifts in historical political speeches using Natural Language Processing (NLP). It provides a web interface for uploading speech text files and visualizes sentiment polarity trends over time.

## Features

- Upload multiple speech `.txt` files
- Analyze sentiment using TextBlob
- Display sentiment polarity scores per speech
- Visualize trends (if plotting is added)
- Simple HTML/CSS frontend with Flask backend

## Demo

A user uploads text files (e.g., `1963_MLK.txt`, `2001_Bush.txt`), and the app returns sentiment polarity scores like:

| Year | Speech Name        | Sentiment Score |
|------|---------------------|-----------------|
| 1963 | I Have a Dream     | 0.78            |
| 2001 | Post-9/11 Address  | -0.20           |

## Project Structureproject/ │ ├── app.py                  # Flask backend ├── templates/ │   └── index.html          # Web interface ├── static/ │   └── styles.css          # Page styling ├── uploads/                # Uploaded files (auto-created) ├── requirements.txt        # Python dependencies └── README.md               # Project documentation
