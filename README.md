# AnimalCrossingNewHorizons
My goal was to assess public opinion on the various 397 villagers in the game "Animal Crossing: New Horizons". 
First, I collected data from Reddit, specifically from the subreddit "r/AnimalCrossing" where users can talk freely about characters. 
At the time I am writing this (4/2020), I went through the top 500 posts as well as all comments within each post within the "Top" category of the subreddit.
I would evaluate public opinion based on NLTK sentimentality analyzer "vader" which was pre-made. 
I went through each post/comment, tokenized each word, and searched for a Villager's name. 
Once identifying the Villager's name, I would implement "vader" to evaluate the sentiment of that sentence. 
I would collect the sentiment score of that sentence containing the villager's name.
In the end, I calculated the mean sentiment score for each villager for each comment/post made for them. F
urther, each Villager has subtypes: gender, personality, and species. 
I also calculated the sentiment scores for each category using the same method for their name. 
Instead of attaching the score to the Villager, I attached it to their gender, personality, or species. 
I also calculated the mean sentiment score for each category type. 
I collected all this data, and made a tidy CSV file containing each villager's sentiment score. 
