# Movie Recommendation System using streamlit

### Dataset link : [TMDM movie dataset(kaggle)](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

- steps:

* first run the movie recommendation.ipynb on kaggle or other platform using the dataset.<br>
* download the similarity.pkl and movie_list.pkl and add to the working directory.<br>
* update path both path in app.py<br>
* using pip install all the dependencies required.<br>
* execute the command <b>" streamlit run app.py "</b> on commnad prompt.<br>
* you're good to Go

## Explanation :

- first preprocessed the data by dropping unnecessary columns
- merging all necessary columns to one column named Tags by removing unnecessary datas in each field.
- finding all pair common words and then finding their common distance using cosine vector
- for one movie id ,showing the nearest five movie id's as recommendation.

<b>credits: CampusX youtube video(i tried it by my own)</b>
