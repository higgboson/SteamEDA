# EDA on steam dataset
* In this data analaysis project , I have performed an exploratory data analyasis on the steam datset, which has 27000 rows of information which mainly consists of features like player count , yearly sales, game developer count, most supported platforms for games
* Majorly cluster based algorithms such as  k means  cluster and DBSCAN have been used , along with a silhoutte score .
# Frameworks used
* **Pandas** - useful for tabulating datset and for accessing any element inside the dataset

* **Matplotlib and Seaborn** - For attractive and rich plots and visualization of datset

* **Sci-kit learn** - For importing and using various feature engineering aspects and for using various ML algorithms

* **Plotly** - This is used for creating interactive plots  for  abetter user experience
 # Features and properties of the dataset
 * Feature engineering is used - Standardisation and normalization(MINMAX) of  features such as prices , playtime  are done in order to get a better numerical analysis
   
 * A new and a  better parameter called Adjusted score is introduced so that we get a uniform rating of all games, this new variable removes the issues caused in games which are not appropriately rated due to very less playerbase and less reviews

 * K means clustering and DBSCAN is used to cluster the data ,  to get a  better understanding, the silhoutte score for  the cluster was found t be 0.56 which shows a moderate to good cluster structure

 * New parametrs such as  various seasons are intoduced to analyze the game sales in each game seasons( to understand which season is  better for sales)

 * Multihot encoding was used to find the platforms supported for each games ( multihot encoding made the data more clear and accessible)

 * A correlation heatmap has been used to show how each of the  parametrs affected each other

 # Outcomes and Observations
   ![image](https://github.com/user-attachments/assets/3802d261-faf1-46c9-8a56-05d7cab3dc3f)

  
  ![image](https://github.com/user-attachments/assets/aa74b84f-c73a-4333-a394-8f064693c2fe)

![image](https://github.com/user-attachments/assets/b90f2b1f-de83-4592-9bc0-096cee259895)

![image](https://github.com/user-attachments/assets/0455a227-d7a4-4806-a8cf-6e2e7d10556d)

![image](https://github.com/user-attachments/assets/6b6a9266-a084-4361-97a9-339760ecdbe7)

![image](https://github.com/user-attachments/assets/abf490e8-53fd-4164-b61c-fd1fe306294a)

![image](https://github.com/user-attachments/assets/7747bff6-e4e4-4d70-96ae-83a71daad805)

![image](https://github.com/user-attachments/assets/89ad993c-1534-42b5-9fce-0891e9077ae3)

<img width="508" alt="image" src="https://github.com/user-attachments/assets/2ee08ac6-e7d6-4f1c-8a0c-a618ced59bb0" />

![image](https://github.com/user-attachments/assets/ff971e9b-2a18-4d07-be26-07283f938c5f)





