#  Movie Recommendation System

## Overview

This project implements a **content-based movie recommendation system** using **TF-IDF Vectorization** and **Cosine Similarity** to suggest movies based on user input.  
The application is built with **Flask** and utilizes the **TMDB API** to fetch real-time movie metadata and posters.

---

## Features

- **Content-Based Filtering:** Recommends movies similar to the input based on cosine similarity of TF-IDF vectors.  
- **Real-Time Data Fetching:** Retrieves movie metadata and posters using the TMDB API.  
- **User-Friendly Interface:** Allows users to input a movie title and receive recommendations instantly.

---

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/IamDurgaPrasad/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```
2. **Install dependencies**

```bash
pip install -r requirements.txt
```
 3. **Set up TMDB API key**

    Obtain an API key from TMDB

    Add your API key to the application configuration (config.py or environment variable).

  4. **Run the application **

       python app.py

Open a browser and go to http://127.0.0.1:5000/ to use the system.

Usage

    Enter a movie title in the input field.

    Click "Get Recommendations" to see a list of similar movies.

    Movie posters and metadata are displayed for easy browsing.

Project Structure
``` 
Movie-Recommendation-System/
├── app.py                # Flask application
├── dataset.csv           # Movie dataset
├── main.py               # Core recommendation logic
├── requirements.txt      # Project dependencies
├── templates/            # HTML templates
│   └── index.html        # Home page
└── static/               # Static files (CSS, JS, images)
```
