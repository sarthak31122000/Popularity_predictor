# Popularity_predictor

<img src="https://user-images.githubusercontent.com/54947362/182036835-bda64a4a-e436-44d4-815e-9e014f6a4488.gif" width="600" height="319" />

We have created a web app using Streamlit and deployed a custom machine learning model that can predict whether any GitHub repository is safe to consume or not just by passing the URL. Here, we generate a score based on the data we scrapped from some famous and random repositories on GitHub.

-   Folder `Notebooks` contains data and script to extract data, analysis of data or the model creation code.
-   We have used github api and Kaggle to collect the github data stored in the file `github_api.csv` and `kaggle_data.csv` respectively which has columns `repo_name`, `star`, `fork`, `watch`, `issue`, `tags`, `most_used_lang`, `discription`, `contributors`, `license`, and `repo_url`.
-   `data_extraction.ipynb` file contains script to extract the information from repositories, `analysis.ipynb` file contains cleaning and visualization operations on the dataset. `model.ipynb` building a machine learning model that can predict which repositories will gain how much `stars` in the future. 😃
