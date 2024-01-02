Author: Kenny Collins
Goal: Refamiliarizing with different data science and ML concepts
Dataset: https://www.kaggle.com/datasets/brendan45774/test-file

For this project, my goal was to apply my understanding of ML concepts. It has been awhile since I have actually coded these concepts since I have been mastering the mathematics and logic behind the algorithms. I will be updating the read me with my thought process as I continue the process.

Current thought train:
My initial thoughts about this problem are what are my limiting factors? I am given a lot of good informaiton like age, sex, class,etc, but despite that there are so many unknowns. I'm going to think on this aspect especially the the correlation between class and surival rate. I'm curious how gender and class can factor into one's survival rate. Will all children have an equal chance at suriving? Were woman and children prioritized or young parents and children? 

Jan 1, 2023:
I finished cleaning the data, and I have different points I plan on testing. I noticed the cabin is missing over 70% of it's values. I would have loved to analyze survival rate based off of room position, but I have class instead. I was missing almost 20% of the age. I thought this category had sufficient data not to drop, so I chose to impute the mean to replace these null values. I plan on testing what returns the best value for this problem. This lead me into visualizing my data before building my models to help me think about my feature engineering. I left off with visualizing the survival rates by age group which I was shocked to see children and elderly had a significantly higher survival rate. I plan on looking through other relationships such as class and survival rate, sex and survival, and sex/age and survival. I think a heatmap would also be super beneficial to my visualization.