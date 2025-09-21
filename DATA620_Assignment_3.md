# Assignment 3

## Data Source
For project 1, I will be using the IMDb Actors Network Dataset from Kaggle.

This dataset models actor collaborations as a network where:  
- Nodes = actors  
- Edges = actors who appeared in the same movie  
- Categorical variable = dominant genre of their work (Drama, Comedy, Action, etc.)  

## Loading Data
- I will download the dataset directly from Kaggle.  
- I will use the actor co-starring relationships provided to create edges between actors.  
- From the data set, I will add to each note their dominant genre as their variable.
- Graph will be loaded in Python NetworkX and export to Gephi for visualizing.  

## Hypothetical outcome using centrality measures
I will compare degree centrality across actor genre groups to see visibility/opportunity differences:  
- Higher average degree for one group could predict more collaboration networks and more future visibility.  
- Lower average degree could indicate negative outcome.  

In this case centrality measures could provide an early signal of outcomes of movies even before seeing box office results or awards.  
