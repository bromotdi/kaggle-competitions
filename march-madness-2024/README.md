# March Machine Learning Mania 2024
#### Forecast the 2024 College Basketball Tournaments

### Link:
![https://www.kaggle.com/competitions/march-machine-learning-mania-2024](https://www.kaggle.com/competitions/march-machine-learning-mania-2024)

### Overview

![image](https://github.com/bromotdi/kaggle-competitions/assets/80320446/5bcf20ee-6532-4630-b0ba-63902e2402d3)

You will be forecasting the outcomes of both the men's and women's 2024 collegiate basketball tournaments, by submitting an portfolio of brackets based on historical data.

### Description
Another year, another chance to predict the upsets, call the probabilities, and put your bracketology skills to the leaderboard test. In our tenth annual March Machine Learning Mania competition, Kagglers will once again join the millions of fans who attempt to predict the outcomes of this year's college basketball tournaments. Unlike most fans, you will pick the winners and losers using a combination of rich historical data and computing power, while the ground truth unfolds on television.

You are provided data of historical NCAA games to forecast the outcomes of the Division 1 Men's and Women's basketball tournaments. This competition is the official 2024 edition, with points, medals, prizes, and basketball glory at stake.

![image](https://github.com/bromotdi/kaggle-competitions/assets/80320446/1a17a021-e9c8-4b4d-ba0d-41e67aa3ece9)

We have made an update to the competition format this year. You will be making bracket predictions for both tournaments, similar to traditional tournament contests, but you will be allowed to submit an entire portfolio of brackets, anywhere from 1 to 100,000.

Please note that submissions to this competition must be made through Kaggle Notebooks. This will enable Kaggle to rerun your submissions using the final qualifying tournament teams, prior to the start of the tournaments. See Code Requirements below for more details on how to submit.

### Evaluation
Submissions are evaluated by their Average Brier Bracket Score.

For both the Men's and Women's tournaments, you will submit a portfolio of bracket predictions. The portfolio should comprise at least 1 and at most 100,000 brackets per tournament. To score this portfolio, we compute the implied probability a team wins each round and evaluate these probabilities against the ground truth using the Brier score independently for each round. We then take the mean of these six Brier scores to compute the overall score. The implied probability is the fraction of brackets a team was predicted to be a winner.

The predictions in each bracket must follow valid tournament paths. In other words, if a team is predicted to win a game in Round N, that team must have also been predicted as the winner of Round N-1 in one of the respective feeder games. The winner of a game in Round 1 must be one of the two teams scheduled to play in that game.

This requirement has consequences for the probabilities derived by the metric. For example, if a team never occurs as a winner in any bracket for some round (that is, has a probability of 0.0 of winning that round), then the probability of winning any future round will also be 0.0.

Each team is identified by a three character string of the form {region}{seed}, where {region} is one of 'W', 'X', 'Y', 'Z' and {seed} is a string of digits from 01 to 16. Note that we do not score the play-in games. We will therefore denote by W16 the winner of the game between W16a and W16b, and similarly for any other play-in teams.

The structure of each bracket is defined by its slots. In rounds 1 to 4, each slot is identified by a four-character string of the form 'R{round}{region}{chalk_seed}'. The {chalk_seed} is the seed, from 1 to 8, of the best possible seed that could appear in that slot. For instance, R1W1. The two Final Four (Round 5) slots are R5WX and R5YZ, and the Championship (Round 6) game slot is R6CH. Each bracket must contain a prediction for every tournament slot.

Please see the heading Data Section 5 files: MNCAATourneySlots and WNCAATourneySlots on the Data page for more on tournament slots.
