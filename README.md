# Book Recommendation System

## Overview

This project is a **Book Recommendation System** built using Python and Streamlit. It leverages a pre-trained KNN model to provide personalized book recommendations based on user ratings and preferences.

---

## Project Files

| Filename                | Description                                     |
|-------------------------|------------------------------------------------|
| `KNN_model.pkl`         | Pre-trained KNN model for recommendations.     |
| `book_names.pkl`        | List or dictionary of book titles.              |
| `df_pivot.pkl`          | Pivot table data used in recommendation logic. |
| `final_ratings.pkl`     | Dataset containing the final book ratings.      |
| `popular_df.pkl`        | Dataframe of popular books after filtering and sorting. |
| `app.py`                | Main Streamlit application script.               |
| `requirements.txt`      | Python dependencies required to run the project.|

---

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



## Requirements

Make sure your `requirements.txt` includes at least:

* streamlit
* scikit-learn
* pandas
* numpy








