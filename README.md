# Card Counter PRO

![IMAGE_ALT](card-counter-pro.png)

Card Counter PRO is a Black Jack Game with features built in to help users learn how to count cards. The game constantly monitors the hand of the user and the dealer and makes a suggestion to the user on whether to hit, stay, double down, or split if possible. These suggestions are based on basic strategy which is a statistically proven method of maximizing your chance of winning any possible hand you can be dealt. Even when a player plays perfect basic strategy, however, they only decrease the house edge to 0.5%, meaning you will still lose on average.

 In order to deal with this, the goal of counting cards is to ensure that even if the player loses more often than they win, when they win, they win bigger. Counting cards determines the times when the player is more likey to win or when the dealer is more likey to win. When the count is up, the player is more likey to win so they will bet higher. When the count is down, the player will bet lower. The count is based on what cards are drawn from the deck. More high cards in the deck are generally considered better for the player. Therefore, when high cards are drawn, the count is decreased. Low cards are generally considered better for the dealer. Therefore, when low cards are drawn, the count is increased. The game keeps track of the count, starting at 0 and increases the count by 1 any time a 2 - 6 value card is dealt. It decreases the count by 1 any time a 10 value card or an ace is drawn. 

Languages: Javascript, HTML, CSS

Libraries and Frameworks: Bootstrap