Summary
=======
This zipped files contains all the necessary notebooks, html, css, csv 
files used in the CZ1016 The Golden Project Recommender System by DS1_G02.

Project Goal: Create a Movie Recommender for Golden Village (Singapore)


credits.csv
=======












CZ1016_PuahYiHao_TohYongLi_WongYingXuan.ipynb
=======
This is the notebook which we used for the project. We compiled all
our code into one notebook that runs sequentially, although the file
size might be large and take time to load.

General Content:
* Data Handling, Cleaning
* Exploratory Data Analysis
* Collaborative Filtering (SVD, ALS, Cold Start)
* Content Filtering (TF-IDF, Cosine Similarity, Custom Defined Function)
* Timing and Location (Application to Business Case)
* Conclusion

Note: Code in Raw NBConvert take a long time to run. We have output to csv some of the results to save time. Those folders should be run.

Webpage
=======
Contains the css, html and py files used to make the webpage.
The csv files used are described the same as those described above, although some files were of older version such as GVmovie as this was used as of the time of making the webpage.


CSS (static)
-------
Folder containing all the css templates used


HTML (templates)
-------
Folder containing all the html pages made for the webpage


Flask (surprise.py, rating_table.py)
-------
rating_table.py contains all the defined functions required to extract out the information.

surprise.py contains the main code for rendering templates and transitioning between pages.
