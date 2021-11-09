# Unsupervised Machine Learning: Cryptocurrency Clustering 💱
<hr>

### Challenge: In this project, I have been given a data set of cryptocurrencies and asked to create a report that includes only those cryptocurrencies that are on the trading market and can be classified into groups to offer as different portfolios for new investment options. 
<hr>

* I started with a dataset of over 1200 cryptocurrencies but after filtering out the product that was not being traded and the product that was no longer being "mined" I was left with 532 different currencies. 
> ![image](https://user-images.githubusercontent.com/83737584/140853023-17706af5-28c6-49a7-879f-3050d1ee9367.png)


* In order to evaluate whether these could be clustered I chose to use an unsupervised machine learning model and used Label Encoding to convert all of the available data to numeric. I used Lable Encoding rather than One-Hot Encoding to decrease the size of the DataFrames being created while still retaining all of the data in the numeric format. 
>![image](https://user-images.githubusercontent.com/83737584/140853241-f502088a-a290-489f-9f48-73c73c884599.png)


* Once this was completed, the data was scaled using Standard Scaler. 

* Dimensionality was then reduced using PCA (Principal Component Analysis) and then data clustering using t-SNE (t-distributed Stochastic Neighbor Embedding) was completed. K-Means, to determine the optimal NUMBER of clusters was then applied to the data. 
>![image](https://user-images.githubusercontent.com/83737584/140852865-838c4e87-4668-4a4c-b803-c87c04ef2c88.png)


## Conclusions: The data CAN be clustered using these methods and the optimal number of clusters appears to be 4. 

> ![image](https://user-images.githubusercontent.com/83737584/140852634-256e2597-101c-4176-999b-55f2391f6b6c.png)


# 💹 But which currencies should be clustered together in each portfolio option?
<hr>

* Once it was determined that not only can the data be clustered but it can be clustered into 4 different portfolio options the question became WHICH cryptocurrencies are best suited to be clustered together?

* To answer this question I created a new data frame consisting of the cryptocurrency names, t-SNE clustering information and a new column of the K-Means classifications to create four separate DataFrames; each consisting of the cryptocurrencies best suited to be included in that investment portfolio. 
>![image](https://user-images.githubusercontent.com/83737584/140853819-b1f915b2-1fce-46b2-9199-7199273db25f.png)



<hr>
Contact:

* https://www.linkedin.com/in/sharon-colson
* sharon.colson@gmail.com
