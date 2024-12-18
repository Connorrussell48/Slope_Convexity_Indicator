# Slope_Convexity_Indicator

Utilizing Moving Averages as a Proxy to Determine Slope and Convexity in the Underlying
Statistics Discussion
Under the conditions described above, there were a total of 122 indications for the bullish trends and 75 indications for the bearish trend across the 4321 trading days studied. The discrepancy between the number of bullish and bearish indications is most likely related to the long-run equity premium in the S&P 500 index. It can be reasonably assumed that this discrepancy would be less pronounced if the strategy was imposed on the index's components. Also, this strategy yielded a signal roughly every 22 days. This frequency of trades could hypothetically be increased through usage across the components of the S&P 500 as well but this could not be tested due to a lack of data for the components in this specific timeframe.
In analyzing the data presented through this initial search, it is clear that the bullish and bearish conditions have a strong ability to forecast the change in trends but are also also susceptible to general market noise. This is evident through the high STD in the duration of the trends with the number of periods that the 200 period moving average increased (decreased) consecutively. Also, there is a wide discrepancy in the ranges in which the peak (trough) price was reached after initiating the indicator. When coupled with the mediocre success rate for both bullish and bearish signals, it is clear that this specific indicator is best used in utilizing the non-linear payoff, such as options. Since there is an This idea will be explored further in the back test. 
Bullish Signals
Number of Signals	122
Average # of periods slope was positive after signal	227.89
Median # of periods slope was positive after signal	179
STD of # of periods slope was positive after signal	203.01
Q1 and Q3 for # of periods slope was positive after signal	63, 323.25
Average # of periods until peak price after signal	148.69
Median # of periods until peak price after signal	69
STD  # of periods until peak price after signal	185.01
Q1 and Q3 for # of periods until peak price after signal	8.25, 237.50
Average peak gain	1.87%
STD of peak gain	2.20%
Median Peak Gain 	0.94%
Q1 and Q3 of peak gain	0.26%, 2.65%
Success rate (peak gain over 1%)	48.36%
Max peak gain 	10.17%
Average drawdown after signal 	-1.14%
Median drawdown after signal	-0.8%
STD of drawdown after signal	1.26%

 
 
Bearish Signals
Number of Signals	75
Average # of periods slope was negative after signal	185.05 
Median # of periods slope was negative after signal	167
STD of # of periods slope was negative after signal	142.72
Q1 and Q3 for # of periods slope was negative after signal	53.5, 260.5
Average # of periods until lowest price after signal	98.67
Median # of periods until lowest price after signal	48
STD  # of periods until lowest price after signal	120.77
Q1 and Q3 for # of periods until lowest price after signal	8.5, 167
Average peak gain	3.5%
STD of peak gain	4.70%
Median peak gain 	1.41%
Q1 and Q3 of peak gain	0.31%, 5.2%
Success rate (peak gain over 1%)	56%
Max Peak Gain 	24.76%
Average drawdown after signal 	1.7%
Median drawdown after signal	1.1%
STD of drawdown after signal	1.59%
 
 
 
Backtest
![image](https://github.com/user-attachments/assets/0ce2b714-e98b-420a-a8a7-c61c987d8f43)
