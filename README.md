# Slot Machine Game

This is a simple Python slot machine game where you can deposit money, place bets, and spin the slot machine to win or lose money. The game allows you to choose the number of lines to bet on and the amount to bet on each line. It then simulates a slot machine spin and determines your winnings based on the symbols that appear on the lines. You can continue playing until you decide to quit.

## Requirements

- Python 3.x

## Instructions

1. Clone or download this repository to your local machine.

2. Run the game by executing the following command in your terminal:

   ```bash
   python slot_machine.py
   ```

3. Follow the on-screen instructions to deposit money, place bets, and spin the slot machine.

4. Press 'Enter' to start playing, and you can press 'q' to quit the game at any time.

## Gameplay

- Deposit money to start the game.
- Choose the number of lines to bet on (between 1 and 3).
- Place a bet on each line (between 1 and 100 dollars).
- The slot machine will spin, and you'll see the results.
- If you win, your winnings will be displayed.
- If you lose, your balance will decrease.
- The game continues until you decide to quit by pressing 'q'.
- You can check your current balance at any time.

## Customize the Game

You can customize the game by changing the following variables in the `slot_machine.py` file:

- `MAX_LINES`: Maximum number of lines to bet on.
- `MAX_BET`: Maximum bet amount.
- `MIN_BET`: Minimum bet amount.
- `ROWS`: Number of rows on the slot machine.
- `COLS`: Number of columns on the slot machine.
- `symbol_count`: Dictionary of symbols and their frequency on the slot machine.
- `symbol_value`: Dictionary of symbols and their corresponding values.

Feel free to modify the game to match your preferences.

## Example Gameplay

Here's a brief example of the gameplay:

```
Welcome to Crystal's Slot Machine!
What would you like to deposit? $100
Enter the number of lines to bet on (1-3)? 2
What would you like to bet on each line? $10
You are betting $10 on 2 lines. Total bet is equal to: $20
A | C | D
B | A | B
C | D | A
You won $20.
You won on lines: 1 2
Current balance is $120
Press enter to play (q to quit).
```

Enjoy the game and have fun!
