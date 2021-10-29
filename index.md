

# Rearrangement-Challenges
Object rearrangement is a critical robot skill broadly applicable in the logistics, industrial, and service domains. Assuming that one object is manipulated at a time, the aim of the problem is to find the optimal manipulation ordering based on an objective. 

As the number of objects grows, the size of the solution space grows exponentially. Combinatorial algorithms need to face the trade-off between computation speed and solution quality. It will be helpful if there is a learning model extracting some useful properties of the problem and leading the search of the combinatorial algorithms in the solution space.

In this competition, we propose three tasks aiming at unveiling the properties of the rearrangement problem with learning methods.

## Challenge 1
Classify each rearrangement instance based on monotonicity, that is, whether the rearrangement problem can be solved by moving each object only once.

## Challenge 2
Given a specific object *o* in the environment, predict whether a non-monotone rearrangement problem can be monotone after *o* is moved away(to an external buffer location).

## Challenge 3
Given a specific object *o* and a buffer location *b* in the environment, predict whether there is a rearrangement plan where *o* moves twice and uses *b* as the intermediate pose while other objects move only once(directly to the goal pose).

## Submit your Works
To join the competition, please click on the invitation link: https://www.kaggle.com/t/a2ab98062a174f40a5544760902bf79a

[This notebook](https://www.kaggle.com/gaokai2021/offline-notebook-for-input-output)  is a submission guide with an offline notebook. If you want to submit with Kaggle's notebook editor, please refer to [this document](https://www.kaggle.com/docs/notebooks#using-the-notebooks-editor).

For further information, please read [this file](https://drive.google.com/drive/folders/1e8MZiwEuZLomWQiRRYQS66benEZPJmBw?usp=sharing).



