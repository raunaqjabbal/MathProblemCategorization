# MathProblemCategorization

## Overview

The goal of this competition is to develop a machine-learning model that can accurately categorize math problems based on the text of the problem. This challenge is an excellent opportunity to apply and sharpen your text classification skills in a unique context, that of Mathematical problems.

Mathematics is a vast field with various sub-domains, each with its unique problem types and solving methods. While it's straightforward for humans, especially educators, to categorize math problems into their respective domains like algebra, calculus, statistics, etc., doing so automatically using machine learning can be a daunting task. However, such automated classification can make it easier for educators to curate problems and help students focus on specific math domains.

## Approach

Initially I used about 8-9 algorithms, and best accuracy was given by Random Forest and SVM(~60%). Not great.

Switched to using LSTMs, got even worse performance due to overfitting.

Finallly, I augmented each sample to increase dataset size by 8-9x, used glove embeddings.

What I could've done: used augmented data and a BERT model, like a model from small-BERT that have less transformer blocks to minimize overfitting. 




## Results

I was given the kaggle competition link 2 days ago, and the kaggle competition closed about 15 days ago. Other teams could've gotten equivalent or higher scores in this 15 day period.
Looing at the public leaderboard, 

Looking at the private leaderboard, my results come at rank 3-4.


![image](https://github.com/raunaqjabbal/MathProblemCategorization/assets/30532162/4b6bfc4b-6f7f-4e20-bfb5-597594030f6f)

Private Leaderboard: 
![image](https://github.com/raunaqjabbal/MathProblemCategorization/assets/30532162/37aad68b-47af-476f-9ce6-e3284ecd85c6)

Public Leaderboard:
![image](https://github.com/raunaqjabbal/MathProblemCategorization/assets/30532162/707f551b-483d-4256-b98e-4dba56ddb250)

