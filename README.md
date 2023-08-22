# Analyzing society's perception of women over time
This is a little research project I did a while ago :) it highlights how language mirrors the zeitgeist of society and shows some fun insights on how the publics perception towards women and feminism has changed.

I analyse how the German language has changed over time, by looking at newspaper headlines from 'die Zeit' from 1946 until 2021, available at https://developer.zeit.de/ 
## Method
I first gathered all available data from the Zeit API in *Data_collection.ipynb* and split the data in different epochs marked by historical events:
- **1946 to 1960**: Post-war Germany, beginning of the DDR before the Berlin Wall
- **1960 to 1990**: Berlin Wall 
- **1990 to 2000**: After the fall of the Berlin Wall
- **2000 to 2010**: 2000s
- **2010 to 2021**: 2010s, early 2020s

In *Data_Preperation_and_Model_Training.ipynb* I prepare the raw words to be used for further processing and finally train word2vec models on each epoch.

In *Data_analysis.ipynb* I take a look at the word embeddings and how the relative semantic meaning of some keywords changes over time.