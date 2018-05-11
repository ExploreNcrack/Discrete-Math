# Coin Weighing

A **coin weighing (or balance puzzle or weighing puzzle)** is a logic puzzle about balancing items to determine which holds a **different** value(counterfeit coin or fake coin), by using balance scales a limited number of times or **minimum number of times**. [[wiki]](https://en.wikipedia.org/wiki/Balance_puzzle)

## Definition 1: 
An  ***adaptive solution*** is a step by step solution where at each step we adapt depending upon the outcome of previous steps.
</br>
notation for finding an adaptive solution:
* "o" be a coin with an unknown weight
* "H" be a coin that might be too heavy but is not too light
* "L" be a coin that might be too light but is not too heavy
* "arrow L" represent the case when the scale tips to the left
* "arrow R" represent the case when the scale tips to the right
* "arrow B" represent the case when the scale balances

## Definition 2:
A **non-adaptive solution** is a solution which all the steps are fully predetermined. 


## Method Use to Solve the Problem
 This is a very typical problem that can be solve with **Divide and Conquer**
 </br>
 </br>**The goal is to isolate the counterfeit coin in minimum of weighings**
 </br>
</br>**CAN NOT USE Divide and Conquer directly to split the coins into two group when the condition of counterfeit coin is NOT KNOWN**

## Facts
* With **known measurement condition** about the counterfeit(fake) coin, the **maximum number** of coin that **one weighing** can determine which is the counterfeit coin is **3**. With any 2 coins on the pan balance, and 1 coin leave not on the pan balance. The result weighing of the 2 coin plus the knowledge of the counterfeit coin will be sufficient to determine which one is the counterfeit coin.
* With **unknown measurement condition** about the counterfeit(fake) coin, the **minimum number** of weighing that can guarentee finding the counterfeit coin is **2**. The minimum number of weighing is 2, that is because we have to figure out the "Good" coin first so that we have a standrad to compare the others to determine which is counterfeit coins.
