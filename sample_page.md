## Professional Networks and Career Opportunities for Directors in Hollywood

**Project description:** The broad theme of my master's thesis is to understand two research questions:
1. Which of the two - connection or merit plays a dominant role in predicting career opportunities in Hollywood
2. Distribution of resources in the industry

**Data:** Data from several sources like IMDb, OMDb, Google search, numbers.com is used to build a network of directors, actors, writers, and production houses based on the movies they have collaborated on. 

**Feature Engineering:** Feature variables for connections are modeled using graph algorithms like centrality and connectedness measures. Merit feature vectors consists of movie ratings, box office collections, awards etc. The target variables are opportunities defined by number of movies, production budgets raised, and career continuity. 

**Models:**
(1) Three models, LASSO regression, random forest, and neural network regressor/classifier, are fit to predict the target variables from the feature vectors.
(2) To understand the resource allocation in the industry, a blockmodel analysis is performed and descriptive statistics are used.

**Findingd:**
- For all three models, it is shown that network variables have higher predictive power implying that connections are more important than merit in determining Hollywod careers of directors.
- Descriptive analysis and the blockmodel analysis show that resources are concentrated at the top and top directors and producers prefer to work with each other.

Tools and models used: 
- Data Collection: OMDb API, BeautifulSoup, MPI, 
- Analysis: [CONCOR](https://www.r-bloggers.com/2015/05/concor-in-r/), AWS Spark, NetworkX, GraphX, scipy
- Visualization: [Gephi](https://gephi.org/), seaborn, MS Excel


See [this](https://github.com/keertanavc/Hollywood-Network-Analysis/tree/master/Network%20Project) directory for codes and the final report.
