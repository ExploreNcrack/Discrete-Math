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
</br>However, this information after weighing is not as useful as divide into 3 groups. Since if divide into 2 groups and do the weighing, we can not tell which one is the "Good"/real coin. We only know the potentially heavier and potentially lighter information.
</br>
</br>
### First Weighing
The best way is to split 8 coins into three groups: 2 groups of 3 coins and 1 group of 2 coin
and then compare the 2 groups of 3 coins by putting one group on each side of the pan balance
</br>
After the first weighing we get following possible cases:
* Tips to  the left side of the pan balance   --> now we know that the left side of the balance are the potentially heavier coins and the right side are the potentially lighter coins
* Tips to the right side of the pan balance   --> the opposite of Tips to the left
* Equivalent balance  --> that tells us that the remaining group of 2 coins are the  counterfeit coin candidates 
