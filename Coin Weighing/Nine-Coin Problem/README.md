# Nine-Coin Problem With One Known Condition Counterfeit Coin
There are 9 coins, all identical except that one is **slightly heavier** than the others. Find the heavy coin using two weighings on a pan balance.

# Solution
One of the very important fact in this problem is that the counterfeit coin is slightly heavier than the others
</br>With this fact, we can quickly determine which side of the balance has the counterfeit coin by checking when side is heavier than the other under the inbalance case
</br>
</br>
**First we need to consider the maximum number of items from which one can find the heavier one in just one weighing. The maximum number possible is three. In order to find the heavier one, we can compare any two coins, leaving the third out. If the two coins are equivalent balance, then the heavier one must be the one not on the balance(third one); otherwise, it is indicated as heavier on the balance.**
</br>
</br>The best way to do it is to apply Divide and Conquer method and **split the 9 coins into 3 groups(each group has 3 coins)**
### First Weighing
Comparing/weighing any 2 groups in the equally splitted 3 groups 
</br>This will result **three possible cases**:
* **Left side** of the balance is heavier --> the counterfeit coin must be in the left side group of 3 coins.
* **Right side** of the balance is heavier --> the counterfeit coin must be in the right side group of 3 coins.
* **Equivalent balance** --> then the counterfeit coin must be in the leftover three coins by exclusion

### Second Weighing
In the second weighing we only have three candidate coins left over to find out which one is the counterfeit coin
</br>
Thus we just need to compare two coins of the three coins 
</br>
From each of the three possible cases above from first weighing, there are three possible cases:
* **Left side** of the balance is heavier -->  the coin in the left side of the balance is the counterfeit coin
* **Right side** of the balance is heavier --> the coin in the right side of the balance is the counterfeit coin
* **Equivalent balance** --> the left over coin is the counterfeit coin

![](https://github.com/ExploreNcrack/Discrete-Math/blob/master/Coin%20Weighing/Nine-Coin%20Problem/sol9.png)

### Total 2 number of weighings is needed in this way. 
