# Auction-Design Tournament

This tournament code is developed by Jinkun Geng. 


How this works:
This time, your task is to write an auction strategy, following the template in auctionStrats; i.e., you will implement a function called auctionStrategy, which takes as input two bid prices and return a 2x2 list to represent the auction results (refer to the comments in the examples)

We will use the bidding strategies submitted for HW3 by you and your classmates, and we will run your auction strategy for these bidding bots. After 10000-round-repeated auction between each pair of these classmates' auto-bidders, we will calculate the revenue earned by your auction strategy as your score. A better auction strategy should enable you to earn more revenue. 

You may use any auction format, as long as:
* On each round it never charges either bidder more than they bid; and
* On each round it allocates the item to at most one bidder. 


Note: For a fixed vector of bids, the all-pay auction will generate the most revenue. But if  in HW3 you and your classmates submitted robust auto-bidders that will shade bids when facing an aggressive auction like all-pay, it may or may not be a good auction for you to use. 



# Objective
Your score is the average revenue earned by your auction strategy. 



# Tasks
You are expected to write a python file named strategy.py (Please keep this name!). In this file you are expected to implement a function named auctionStrategy. After you finish you code, put the strategy.py to the folder auctionStrats, run the game_run.py.


We have made three examples in auctionStrats, i.e., first-price based auction, second-price based auction, and all-pay auction. You should design your own auction strategy to earn the most revenue. 



# Tips

To start from a clean Python enviornment, I suggest you use conda 

https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html

First, install conda

Second, create a clean python enviornment (say python 3.7) with conda

Third, install any deps and execute your script in that conda enviornment 

The major commands are as below. 

```
conda create --name [NAME]

conda activate [NAME]

conda install pip

pip install -r requirements.txt
```

After you have successfully create the environment, enter the code environment, and run game_run.py

```
cd code 

python game_run.py
```


# Note

All you need to do is to write a strategy.py file and add it to auctionStrats. No need to change any existing files.

When submitting to gradescope, you only submit strategy.py, no other files are needed.

For any questions, feel free to make a post on edstem.
