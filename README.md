# Calories Tracker App

A simple and efficient web app to track your daily calorie intake using **Google Gemini** for natural language processing and **Streamlit** for the user interface.

## Features

- Natural language input for meal descriptions using Google Gemini.
- Real-time calorie estimation.
- Daily summary of calories consumed.
- Interactive charts and visualizations with Streamlit.
- Easy to use and mobile-friendly.

## Demo

![App Screenshot](path_to_screenshot.png)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/calories-tracker.git
   cd calories-tracker
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

## Project Structure 
calories-tracker/
├── app.py              # Main Streamlit app
├── requirements.txt    # Python dependencies
├── README.md           # This file
├── .env                # API keys (not committed to git)
└── utils.py            # Helper functions (e.g., API calls)
