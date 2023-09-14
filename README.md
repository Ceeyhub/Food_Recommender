# Food and Recipe Recommender

## Project Goals
To create a recommender system that will assist users in finding recipes that match the ingredients they currently have in their kitchen and recommend similar recipes based on their preference.
## Process
#### Data Collection
For this project the dataset was selected from kaggle (https://www.kaggle.com/datasets/irkaal/foodcom-recipes-and-reviews)

#### Data Preprocessing and EDA
- Dropped null values and checked for duplicates
- Dataset had over a million recipes so created a sample dataframe

![image](https://github.com/Ceeyhub/Food_Recommender/assets/134983985/65e4ec12-0d6b-4946-8411-c584d47dcadb)

![image](https://github.com/Ceeyhub/Food_Recommender/assets/134983985/a1f6c000-be82-4d11-98a9-bbddd280bcdc)
Wordcloud of Keywords

#### Recommender Systems
![image](https://github.com/Ceeyhub/Food_Recommender/assets/134983985/1038c96a-4a9a-44b2-aca9-ed41a6efb481)

![image](https://github.com/Ceeyhub/Food_Recommender/assets/134983985/fdbfd718-2b00-46cb-a135-eb54db9be773)

## Results
Created two recommender systems using NLP, first to recommend recipes based on available ingredients and
dietary needs, and a second recommender to suggest recipes based on users history

#### Challenges
- Data Sourcing – Spoonacular API
- Handling large dataset – long code run time

#### Future Goals
- Deployment - for users to input their preferences and view recipe recommendations
- Better workstation to handle recommendation system using more recipes


