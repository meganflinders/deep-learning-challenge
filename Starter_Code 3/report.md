# Overview
The purpose of this analysis was help a nonprofit foundation decide which organizations to provide funding to  by creating a binary classifier using Alphabet Soup's historical funding data that can predict the applicants success.
#Results
* The target for my model was the "IS_SUCCESSFUL" column in the dataset. 0 meaning they were unsuccessful and 1 meaning they were successful.
* The features of my model were the columns 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'ORGANIZATION', and 'INCOME_AMT'
* I removed  the 'EIN', 'NAME', 'USE_CASE', and 'SPECIAL CONSIDERATIONS' as they were neither targets nor features
* There were 43 neurons and 3 layers in my first model,  36 neurons and 5 layers in  my second model, and 32 neurons and 5 layers in my third model which ended up yielding the highest accuracy of preidctions. I found that the fewer the neurons and the more layers but no more than 5 produced the most accurate predictions
* I was unable to achieve the target model performance
* In order to achieve higher accuracy with my model, I attempted to remove as many irrelevant columns from the dataset that I could, and then kept adding different layers with different activation codes until I was able to achieve a better result.

#Summary
Because I was unable to achieve the target model performance, I would recommend using a different model to predict funding success 