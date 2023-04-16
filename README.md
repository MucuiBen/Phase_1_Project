# Introduction:¶
Microsoft is launching a new movie studio and wants to understand the current market trends to make informed decisions about the type of movies to produce. In this exploratory analysis, we will focus on the original language, return on investment (ROI), and vote average to identify popular movie trends and help Microsoft make data-driven decisions.

# Data:
To perform this analysis, we will use data from various sources, including Box Office Mojo, IMDB, Rotten Tomatoes, The MovieDB, and The Numbers. These datasets contain essential information about movies, such as box office earnings, budget, language, and ratings.

bom.movie_gross.csv.gz: This dataset contains information about movie gross earnings, studio, and release date from Box Office Mojo.
tmdb.movies.csv.gz: This dataset contains information about movies including budget, revenue, genres, and release date from The Movie Database.
tn.movie_budgets.csv.gz: This dataset contains information about movie budgets, revenue, and release date from The Numbers.
rt.movie_info.tsv.gz: This dataset contains information about movie ratings, genres, directors, and actors from Rotten Tomatoes.
We will use these datasets to explore the relationship between various features such as genre, budget, ratings, and box office performance.

# Features of interest:
We will focus on three main features to guide our analysis:

Original Language: We will explore the popularity of movies based on the original language used in production.

Return on Investment (ROI): We will investigate the correlation between a movie's budget and its box office performance to determine the ROI.

Vote Average: We will examine the relationship between a movie's vote average and its box office earnings to determine if movies with higher vote averages tend to perform better.

Overall, this analysis aims to provide Microsoft with insights on the popular movie trends based on language, ROI, and vote average to help them make informed decisions about their new movie studio.
# methodology
This project involved an exploratory data analysis approach to analyze the movie data obtained from publicly available sources such as The Movie Database (TMDb) and IMDB. The data was cleaned, preprocessed, and merged into a single data frame (df2) for analysis.
To address the research questions, descriptive statistics and visualizations such as histograms, scatter plots, and box plots were used to explore the relationship between the variables of interest.
 In addition, correlation analysis was performed to quantify the strength and direction of the relationship between variables.
Python programming language and several data analysis libraries such as pandas, seaborn, and matplotlib were used to perform the data analysis.
This approach allowed us to gain important insights into the relationship between variables of interest and answer our research questions formulated.
![image](https://user-images.githubusercontent.com/127657429/232335985-80a97a76-51b4-4692-9e47-f1fe588da41d.png)
# Data characteristics
The data was obtained from publicly available sources such as Box Office Mojo, IMDB, Rotten Tomatoes, The Movie DB, and The Numbers. 
These datasets contain essential information about movies, such as box office earnings, budget, original language, budget, release date,  ratings etc.
The original language variable includes over 20 different languages, with English being the most common language used in production.
The budget and revenue variables have a wide range of values, with some movies having very high budgets and revenues, while others have much lower budgets and revenues.
The data set includes some missing values, particularly in the budget and revenue variables, which were imputed using the mean values for the respective variables.
The data set contains outliers in some variables, particularly in the budget and revenue variables, which were addressed using logarithmic transformation to improve the normality of the data.
![image](https://user-images.githubusercontent.com/127657429/232336156-d58c80e3-3d8f-40a2-a117-4d6efd2ab9ad.png)
