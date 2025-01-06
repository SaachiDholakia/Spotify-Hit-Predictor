# Spotify-Hit-Predictor



```markdown
# Harmonizing Hit Predictions

## About the Project
This project, "Harmonizing Hit Predictions: Leveraging Audio Features to Forecast Spotify's Top Songs", aims to develop a predictive model that can forecast the likelihood of songs hitting the Spotify Top Songs chart. Using a comprehensive dataset pulled via Spotify API, this model assesses various audio features and predicts whether a song will be popular or not.

### Team Members
- Dylan Kakkanad
- Priyanka Chaudhari
- Saachi Dholakia
- Sahasra Konkala

## Getting Started

### Prerequisites
- Python 3.8+
- Spotify API access
- Libraries: pandas, numpy, sklearn, spotipy

### Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/harmonizing-hit-predictions.git
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
To run the project, execute the following command:
```bash
python run_model.py
```

## Dataset
The project utilizes data from Spotify, featuring audio features of tracks. The initial dataset consists of 92,233 tracks with 20 different features such as danceability, energy, key, loudness, and popularity.

## Model Overview
We explored several machine learning models, including:
- Random Forest Classifier
- Support Vector Classifier
- K-Nearest Neighbors
- Logistic Regression

## Performance
The models' performance was evaluated based on accuracy and balanced accuracy. Here are the results after hyperparameter tuning:
- **Random Forest Classifier**: 77.32% Accuracy, 58.56% Balanced Accuracy
- **Support Vector Classifier**: 63.45% Balanced Accuracy
- **K-Nearest Neighbor**: 60.51% Balanced Accuracy
- **Logistic Regression**: 60% Balanced Accuracy


This README template includes all the essential sections, such as about the project, getting started instructions, model overview, performance summary, contributions, licensing info, contact, and acknowledgements. Adjust as necessary based on your specific GitHub project needs.
