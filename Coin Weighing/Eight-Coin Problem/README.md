# Eight Coin Problem With One Unknown Counterfeit Coin
There are 8 coins, all identical except that one is **slightly heavier or slightly lighter** than the others.
</br>
Find the counterfeit using three weighings on a pan balance.

# Solution
This problem is slightly different than the Nine-Coin problem
</br>**Since the condition about whether the counterfeit coin is heavier than the others or lighter than the others is not known in this case.(which means we have to assume both cases counterfeit coin is slightly heavier or slightly lighter)**
</br>
</br>**Thus we can not apply divide and conquer directly to the problem in this case.**
</br>Since if we directly split the coins into 2 groups, there are two possible cases result (either left side heavier or right side heavier)
</br>However, this information after weighing is not useful at all. Because the counterfeit coin can be any one of these eight coins

