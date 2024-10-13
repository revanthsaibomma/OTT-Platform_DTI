1. Introduction
1.1 Motivation
During the pandemic lockdown, the popularity and use of Over-The-Top (OTT) platforms surged as people stayed indoors. This project aims to explore the differences between four major OTT platforms—Netflix, Hulu, Prime Video, and Disney+—by analyzing a dataset from Kaggle. The dataset includes information on the movies available on these platforms. The goal is to understand how these platforms compare and also to derive global movie insights.

1.2 Dataset
The dataset used in this project was provided by Ruchi Bhatia on Kaggle. It contains information about movies on various OTT platforms, including features like:

Title
Genre
Year of release
Platform availability (Netflix, Hulu, Prime Video, Disney+)
1.3 Acknowledgements
Ruchi Bhatia for the dataset on Kaggle: Movies on Netflix, Prime Video, Hulu, and Disney+
ZhongTr0n for the tutorial on creating a map from categorical data: Create a Categorical Choropleth with Python
2. Data Collection and Preparation
2.1 Data Import
The dataset is imported using pandas and further processed for analysis. Key libraries used include:

pandas: For data manipulation
numpy: For numerical operations
matplotlib and seaborn: For data visualization
The data is loaded and checked for missing values and inconsistencies before proceeding with analysis.

3. Exploratory Data Analysis (EDA)
3.1 Distribution of Movies Across OTT Platforms
The first step of the analysis involved understanding the distribution of movies across the four OTT platforms:

Netflix
Hulu
Prime Video
Disney+
Visualizations such as bar charts and pie charts were used to show the percentage of movies available on each platform.

3.2 Popular Genres
By analyzing the genre distribution on each platform, the report provides insights into which genres are most popular on each service. For example, Netflix might have a higher number of documentaries, while Disney+ is likely to focus more on family-friendly content.

3.3 Year-wise Distribution
The dataset was analyzed to identify the release year distribution of movies on each platform. A time series plot was used to show how many movies were added each year on each platform, providing insights into trends in movie releases.

4. Key Insights
4.1 Platform-wise Analysis
Netflix: Known for a wide variety of genres, including documentaries and original content.
Prime Video: Offers a diverse set of movies, including many from smaller production houses.
Hulu: Contains a mix of TV shows and movies, often focusing on niche content.
Disney+: Primarily family-oriented content, with a strong emphasis on animated and children’s movies.
4.2 Global Insights
The dataset also reveals some interesting trends across all platforms:

Certain genres, such as action and drama, are universally popular.
Movies from particular years, such as the late 1990s and early 2000s, are prevalent across multiple platforms.
5. Conclusion
This analysis of movies across Netflix, Hulu, Prime Video, and Disney+ during the lockdown period has provided several insights into the type of content available on each platform. The platforms differ not only in the volume of content but also in the types of movies they feature. Netflix, for instance, has more variety in its content, whereas Disney+ is focused on family entertainment.

Further analysis could include deeper dives into user ratings or exploring trends in TV shows across platforms.

6. References
Dataset source: Ruchi Bhatia’s Kaggle dataset: Movies on OTT Platforms
Tutorial for data visualization: Create Categorical Choropleth with Python

