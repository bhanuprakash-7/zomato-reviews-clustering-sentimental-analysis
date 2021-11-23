# zomato-reviews-clustering-sentimental-analysis
# Problem Statement 
Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus and user-reviews of restaurants, and also has food delivery options from partner restaurants in select cities.  India is quite famous for its diverse multi cuisine available in a large number of restaurants and hotel resorts, which is reminiscent of unity in diversity. Restaurant business in India is always evolving. More Indians are warming up to the idea of eating restaurant food whether by dining outside or getting food delivered. The growing number of restaurants in every state of India has been a motivation to inspect the data to get some insights, interesting facts and figures about the Indian food industry in each city. So, this project focuses on analysing the Zomato restaurant data for each city in India.  The Project focuses on Customers and Company, you have to analyze the sentiments of the reviews given by the customer in the data and made some useful conclusion in the form of Visualizations. Also, cluster the zomato restaurants into different segments. The data is vizualized as it becomes easy to analyse data at instant. The Analysis also solve some of the business cases that can directly help the customers finding the Best restaurant in their locality and for the company to grow up and work on the fields they are currently lagging in.  This could help in clustering the restaurants into segments. Also the data has valuable information around cuisine and costing which can be used in cost vs. benefit analysis  Data could be used for sentiment analysis. Also the metadata of reviewers can be used for identifying the critics in the industry
# Attribute Information
# Dataset - Zomato Restaurant names and Metadata
    Name : Name of Restaurants
    Links : URL Links of Restaurants
    Cost : Per person estimated Cost of dining
    Collection : Tagging of Restaurants w.r.t. Zomato categories
    Cuisines : Cuisines served by Restaurants
    Timings : Restaurant Timings
    
# Dataset - Zomato Restaurant reviews
    Restaurant : Name of the Restaurant
    Reviewer : Name of the Reviewer
    Review : Review Text
    Rating : Rating Provided by Reviewer
    MetaData : Reviewer Metadata - No. of Reviews and followers
    Time: Date and Time of Review
    Pictures : No. of pictures posted with review
    
    
# SUMMARY
As the restaurants are increasing day by day, it has been difficult for people to
choose a restaurant over others. And for the restaurant owners, they need to understand
what they are lacking behind.
Our project’s objectives are to cluster the restaurants, so that people can easily
chose the restaurant they want. And sentiment analysis to analyze the reviews given by
the reviewers/ critics. And EDA which can solve some business case problems.
At first, we used K-Means Clustering approach without scaling the features in order
to give priority to the cost and average ratings columns. Clustering was done on the basis
of cost and average ratings, so that people can choose affordable and better restaurant.
And afterwards, we used we used K-Means Clustering approach with scaling. And we
performed dimensional reduction using Principal Component Analysis (PCA). Then, the
data was clustered based on cuisines, so that people can chose the restaurants based on
what they want to have.
The total nine thousand reviews are mapped with sentiment score which was
retrieved from polarity score from Text Blob which were further classified into positive,
negative and neutral. So, with these we can easily retrieve the main phrases that were
repeated in most of the reviews. From which Restaurants can check in which aspect they
were lacking. The average rating which was given in dataset and the average sentiment
score of the reviews which were calculated based on the sentiment score were compared.
Some of the ratings given badly just because of packing and delivery issues. So, it’s better
to store individual ratings for all the categories.
