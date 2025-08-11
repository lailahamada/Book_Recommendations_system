# Book Recommendation System

## Overview

This project is a Book Recommendation System developed using Python and Streamlit. The system is designed to help users discover books tailored to their tastes by analyzing historical user ratings and preferences. It leverages collaborative filtering techniques, specifically a K-Nearest Neighbors (KNN) algorithm, to identify patterns in user behavior and recommend books that similar users have enjoyed.

The core idea behind the recommendation engine is to find users with similar reading and rating habits, then suggest books that those similar users liked but the current user hasn’t read yet. The model builds a user-item matrix from the dataset, capturing users’ ratings for various books. Using this matrix, the KNN algorithm calculates similarity scores between users to find the closest neighbors.

---

## Project Files

| Filename                | Description                                     |
|-------------------------|------------------------------------------------|
| `KNN_model.pkl`         | KNN model for recommendations.     |
| `book_names.pkl`        | List or dictionary of book titles.              |
| `df_pivot.pkl`          | Pivot table data used in recommendation logic. |
| `final_ratings.pkl`     | Dataset containing the final book ratings.      |
| `popular_df.pkl`        | Dataframe of popular books after filtering and sorting. |
| `app.py`                | Main Streamlit application script.               |
| `requirements.txt`      | Python dependencies required to run the project.|

---
## Requirements

Make sure your `requirements.txt` includes at least:

* streamlit
* scikit-learn
* pandas
* numpy

## How to Run Locally

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <project-folder>
    ````

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

---

## Deployment

### Deploying on Streamlit Cloud

* Connect your GitHub repository to [Streamlit Cloud](https://bookrecommendationssystem-wu6q9w86p8he5y2d4jap36.streamlit.app/).
* Select the repository and deploy the app.
* Streamlit Cloud automatically sets up the environment based on `requirements.txt`.










