
# About

- This study aims to understand prominent topics surrounding mental health in Singapore from Reddit Forums.

# Data
- Data was stemmed from 4 reddit forums: 
    - `r/askSingapore`
    - `r/Singapore`
    - `r/singaporeraw`
    - `r/SingaporeR`

- Dates from Jan 2015 to December 2022
- N=379,787 original posts
- n=2783 posts identified to be relevant to mental health


# Methods
1. **Chain-of-thought** prompting was used to identify Reddit posts related to mental health
2. **BERTopic with MMR-based fine-tuning** was used to key topics related to mental health. 

# Table of Contents  

> Codes
>> 1_data_collection.ipynb  
>> 2_COT_classifier.ipynb   
>> 3_BERTopic.ipynb   
>> 4_temporal_visualization.ipynb   
>> 5_LIWC_analysis.ipynb   


> Plots  
>> LIWC  
>> plot_categories.jpg  
>> plot_topics.jpg  

> readme.md  

- `Codes` contains all the codes and should be self-explainatory.  
- `LIWC` in the plots are the plots for the `LIWC` analysis, `plot_topics.jpg` are the dynamic / temporal topic modeling plots and `plot_categories.jpg` is the same but grouped to categories. 
