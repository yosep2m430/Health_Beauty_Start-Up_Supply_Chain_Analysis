# Health_Beauty_Start-Up_Supply_Chain_Analysis

![image](https://github.com/yosep2m430/Music-Recommendation-System/assets/102874665/56998e02-0b0f-494a-ab0e-751fc23c038c)

*Spotify is a continuously growing audio streaming platform serving both artists and listeners worldwide. With increasing competition, Spotify has seen a slow decline in its market share. Our goal is to develop a data-driven recommendation system to better cater to users’ tastes.* 

## 1.Data
A CSV file containing product data, associated costs, revenues, and routes data was obtained from Kaggle:<br>
https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis<br>


## 2.Data Cleaning and Exploratory Data Analysis (EDA)
[Exploratory Data Analysis (EDA).ipynb](https://github.com/yosep2m430/Song-Recommendation-System-Capstone-3-/blob/main/Exploratory%20Data%20Analysis%20(EDA).ipynb)<br>
In Exploratory Data Analysis (EDA), the relationships between audio features and the relationships between user, tracks, and playlists are explored.<br>

### User-playlist dataset
<img width="917" alt="image" src="https://github.com/yosep2m430/Music-Recommendation-System/assets/102874665/18529009-752e-48d1-9590-40cd85e37504"><br>
Although overall counts are the same, we can see that there are more unique tracks and artist names than listeners and playlists. This makes sense, given that listeners tend to add more than one songs to each of their playlists. We can also see that there are more playlists than listeners. This may be from listeners with more than one playlists. Finally, there are more tracks than artists. This may be because listeners may save more than one track by a given artist (hence favorite artist(s))! <br>


### Audio feature dataset
<img width="896" alt="image" src="https://github.com/yosep2m430/Music-Recommendation-System/assets/102874665/619aaa9d-f1ea-4924-82d9-c6831386da40"> <br>
This lineplot shows that different audio features stayed consisted throughout 1921- 2020. This is suprising, given the change in both diversification of musical style and in popular taste <br>


<img width="912" alt="image" src="https://github.com/yosep2m430/Music-Recommendation-System/assets/102874665/9a78934b-18c8-419e-bfb7-e71834ed69d2"><br>
Because we are working with high-volume, high-dimensional data, I performed dimensional reduction and cluster to visualize our data. The massive list of top charting songs can be broken down into eight different clusers.<br>

## 4.Modeling
- In [Modeling.ipynb](https://github.com/yosep2m430/Song-Recommendation-System-Capstone-3-/blob/main/Modeling.ipynb), collaborative-filtering model, content-based filtering model, and hybrid model are explored.
- Hybrid model was able to find user with similarity of 0.816.

## 5.Future Improvements
I would love to work with more detailed data if it is available somewhere. More specifically, I would love genre-specific user-playlist dataset and audio feature dataset. Being able to target songs within users' genre of choice will allow one to recommend songs that users would find even more enjoyable. 

## 6.Project Report
[Final Project Report](https://github.com/yosep2m430/Music-Recommendation-System/blob/main/Final%20Project%20Report-%20Music%20Recommendation%20System.pdf)
