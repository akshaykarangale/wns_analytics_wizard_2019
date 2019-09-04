# WNS Analytics Wizard - 2019

In this problem, the task was to predict the probability of the user clicking the ad on the basis of historical view log data, ad impression data and user data.

The evaluation metric was: AUC-ROC

#### Public Leaderboard Score: 0.757398 (10th Place)
#### Private Leaderboard Score: 0.75287 (3rd Place)

#### Instructions to reproduce solution:
* Run "WNS-adClick_1.ipynb" to generate "sub_1.csv" using competition datasets as inputs
* Run "WNS-adClick_2.ipynb" to generate "sub_2.csv" using competition datasets as inputs
* Run "ranking_avg_script.py" using "sub_1.csv" and "sub_2.csv" as inputs to generate "final_submission.csv"

Detailed approach can be found in "WNS Analytics Wizard - 3rd place approach.pdf"
