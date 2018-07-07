# Moviereviews
![image of movie](/images/movies2.png)
Can you predict the financial success of a movie simply based on its tagline?  It turns out the answer is a few more features than just tagline would help improve   accuracy, but there is still some predictive power in just the topic.  Plus, the analytics are fun to explore.  This is a text analytics problem since the only features you have are the text tagline and the target variable which is the revenue the movie generated.  
## Business Scenario
Predicting the financial success of a movie prior to its release is an important goal for movie producers.  Having some idea of what the revenue may be enables appropriate allocation of scarce resources to maximize their return on investment.  Its also helpful to have some idea about how much a movie may make as early as possible in the production lifecylce, such as during the moving planning phase or even during script reviews, to guide investment and production-related decisions.  No one wants to spend way too much in production just to have a box office failure.  
## Analysis
The source data for this analysis consists of the storylines from 1000 movies produced from 2000 to 2006, and how much revenue each movie made.  The data was downloaded from a prior Kaggle competition.  The following shows the first few rows of data in the file. 
![image of data](/images/data.png)
The target variable is CategoryGross

The data looks like The variable CategoryGross is a bucketed nominal value that describes the range of revenue that each movie generated.  Figure 2 shows the revenue categories in each bucket.   Figure 3 shows how the revenue is distributed across all the movies.   

