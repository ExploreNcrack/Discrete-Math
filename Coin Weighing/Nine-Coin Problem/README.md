# Nine-Coin Problem 
There are 9 coins, all identical except that one is **slightly heavier** than the others. Find the heavy coin using two weighings on a pan balance.

# Solution
One of the very important fact in this problem is that the counterfeit coin is slightly heavier than the others
</br>With this fact, we can quickly determine which side of the balance has the counterfeit coin by checking when side is heavier than the other under the inbalance case
</br>
</br>The best way to do it is to apply Divide and Conquer method and **split the 9 coins into 3 groups(each group has 3 coins)**
### First Weighing
Comparing/weighing any 2 groups in the equally splitted 3 groups 
</br>This will result **three possible cases**:
* **Left side** of the balance is heavier --> the counterfeit coin must be in the left side group of 3 coins.
* **Right side** of the balance is heavier --> the counterfeit coin must be in the right side group of 3 coins.
* **Equivalent balance** --> then the counterfeit coin must be in the leftover three coins by exclusion

### Second Weighing


