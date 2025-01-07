# Slot Machine

## PRECAUTIONARY STATEMENT 
" I DO NOT PROMOTE / ADVOCATE GAMBLING. THIS IS JUST A FUN PROJECT TO SHOWCASE MY PYTHON SKILLS "

## PROJECT SUMMARY
I have created a slot machine in this repository using Python on vscode. this slot machine takes a deposit as input from the player and asks how many lines do they want to bet on. Based on the winning/losing result give out the remaining balance and ask if the player wants to quit or play again. 

## PROJECT AIM
This project aims to show my Python programming skills, understanding of complex data structures, and problem-solving. 

## PROJECT PREREQUISITE
1. [Python3](https://www.python.org/downloads/)
2. [VS Code](https://code.visualstudio.com/download)

## STEPS TAKEN
1. I started this project by understanding how a slot machine functions and what features it should have. A slot machine should accept deposits, ask after each turn if the player wants to continue playing, and ask how much he/she wants to bet on each line, how much they won and the balance they have after each win/loss.
2. The only module I imported for this project was "random"
3. In the next step, I decided the maximum number of lines they could bet on, what amount minimum and maximum they could bet on each line and made a dictionary of symbols depicting the amount and the number of times they can occur in each spin.
   - A: Can occur twice each spin and it will give 10 times the amount they bet on  it
   - B: Can occur 4 times each spin and it will give 5 times the amount they bet on it
   - C: Can occur 6 times each spin and it will give twice the amount they bet on it
   - D: Can occur 8 times each spin and it will give back the amount they bet on it.
To keep this project simple I have not taken into account losses for now.
4. There are a total of 8 functions that help to run this slot machine. Those functions are as follows:
   1. Check winnings: This function checks if the player has won and if yes, how much is their winning amount. 
   2. Get slot machine spin: This function uses the random module to spin the slot machine. It randomly selects symbols based on the dictionary but as we have already adjusted the number of times an alphabet can occur, we can adjust the win and loss ratio. 
   3. Print slot machine: This function prints the slot machine lines to show what line/lines the player has won on. 
   4. Deposit: This function takes an amount as input from the player. This amount is the deposit that players want to play with on this machine. 
   5. Get the number of lines: This function takes an integer as input from the player. The player can select if he wants to bet on 1, 2 or 3 lines each turn. 
   6. Get bet: This function also takes input from the player. The player can select how much amount of bet he wants to place on each line. The minimum is 10 and the maximum is 100. 
   7. Spin(balance): This function takes into account the balance that was returned from the balance function. Here, the machine checks if the player has enough balance to place his bet. this function also prints the amount the player is betting, which line the player is betting on and what balance is left. This function also returns what amount the player won. 
   8. Main: This function asks the player if he wants to continue to play or quit. 

## LIMITATIONS
- This slot machine takes into account 3 rows and 3 columns. Usually slot machine has more than 3 rows and columns.
- This slot machine doesn't take losses into account and the worst result a player can have is getting no profit.
- This slot machine also uses alphabets as symbols.
- This slot machine has a minimum and maximum limit that a player can bet on each line.
- This machine only allows betting from top to bottom order so if the player selects 2 lines he can only bet on 1st and 2nd line but not 1st and 3rd line. 
