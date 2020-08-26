# Will the Washington Capitals Ever Win a Stanley Cup?

Stats and numerical analysis is making its way into hockey. 
We can analyze the 2016-2017 Washington Capitals Stanley Cup chances using historical data to model the likelihood they win the Cup.


Most published data is heavily correlated, as we see below. This is usually because common stats are based off different combinations of
  - Goals scored
  - Time on ice
  - Goals against

![corr_stats](https://github.com/mathyjokes/Wash-Caps-Stanley-Cup/blob/master/correlated_variables.png)

A logistic regression of the available data, necessary because the Stanley Cup is a win-it or lose-it event, can be analyzed to determine the most important features for classification.
Goals scored comes up as feature with most effect on winningness prediciton, perhaps unsurprisingly to anyone who has played a sport.

Based on a logistic regression of available data, the Caps are not destined to win the Stanley Cup in 2017. They need to score more goals!
