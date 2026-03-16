# The task

The firs task is to use Califonia Census data to build a model of housing prices in the state. This data includes metrics such as: 
* population
* median income
* median housing price for each block in the state of California

Block groups are the smallest geographical units for which the US Census Bureau publishes sample data.

**The model should learn from this data and be able to predict the median housing prince in any district, given all the other metrics**


## Questions to ask: 

 * Is it supervised, unsupervised or Reinforcment learning?
     * **Answer:** Supervised

 * Is it a classification task, a regression task or something else?

    * **Answer:** Regression task

 * Should you use batch learning or online learning? 

    * **Answer:**   batch learning



## Select a performence Measure

We will use the **Root Mean Square Root**  or **Mean Absolute Error**. Both of them are ways to measure distance between 2 vectors (the vector of predictions and the vetcor of target values) 