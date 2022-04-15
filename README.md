# IMDb_Movies_Exploratory_Data_Analysis
Exploratory data analysis of IMDb dataset

### 1. Overview
IMDb Movies is a dataset that includes the top 100 highest-ranked films from the previous decade, as well as numerous bits of information on the film, its cast, and the voters who have rated these films. The objective is to use Python and its modules to uncover some intriguing insights about these films and their audiences.

### 2. Methodology
- Importing and inspecting the Data
- Data cleaning and manipulation – changing the scale of gross and budget, adding profits column, averaging reviews by general audience and critics.
- Visualising data through various plots and drawing insights from them

### 3. Libraries used
*Numpy, Pandas, Seaborn, Matplotlib*

### 4. Inferences
- If we remember, the movie ‘Tangled’ was one of the highest-grossing movies in the year 2019. Despite that, the dataset seems to be telling a different story, that it had negative profits. After examination from external sources, it can be inferred that the dataset accounts for only domestic gross and not worldwide gross.
- Regarding the popularity of the actors based on the number of Facebook likes, the trio of DiCaprio, Tom Hardy, and Joseph Gordon-Levitt makes it to the top, under the condition that none of the three actors' Facebook likes is less than half of the other two
- Most movies are around 2 hours long.
- ‘Deadpool’ is the most popular R rated movie among the Under-18 group

#### Demographic Analysis by Genre and Gender
- Age group 18-29 has voted more than any other group in both males and females.
- In the age group of Under 18 males, Sci-Fi is the popular genre, whereas Animation is most popular among under 18 females
- Romance is the least voted genre by all age groups in males.
- Among the active voters i.e. 18 - 29 age group, Romance is the least rated genre among males and Crime among females
- Drama with the highest number of movies is rated the lowest by 45 and above in males and 30-44 in females.
- Romance is the least rated genre among above 45 males and females.

#### US vs non-US Cross Analysis
- US movies have received higher ratings from US and non-US voters in general when median ratings are considered
- The ratings from non-US voters are more narrowly distributed than those by US voters.
- Some US movies have received an extraordinarily high number of ratings by both US and non-US voters. There are no such outliers in the case of non-US movies.
- The number of votes for non-US movies is uniformly spread implied by their interquartile ranges.

#### Voting by Top 1000 voters
- Drama, which had the most number of movies produced, is not greatly voted by the top 1000 voters.
- The voting pattern is similar to that for different age groups
- The genre of Romance seems to be most unpopular among the top 1000 voters.

**5. References -** 
This case study was a part of Data Science Certification Program by UpGrad Campus.

#### 6. Author -  **K Rakesh** [LinkedIn profile](https://www.linkedin.com/in/rakesh-k-34b48516b/)

