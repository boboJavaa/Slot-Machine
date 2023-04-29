# Slot Machine Game

This is a simple slot machine game made in Python. It allows you to bet on multiple lines and win money based on the symbols you get.

## How to Play

1. Run the program by typing `python slot_machine.py` in the command line.
2. Enter the amount you want to deposit.
3. Enter the number of lines you want to bet on.
4. Enter the amount you want to bet on each line.
5. Press enter to spin the slot machine.
6. If you win, the amount you won will be displayed, and the winnings will be added to your balance. If you lose, the amount you bet will be subtracted from your balance.
7. You can keep playing by repeating steps 3-6. If you want to quit, type `q` when prompted to spin the slot machine.

## Configuration

You can modify the following constants in the code to change the behavior of the game:

- `MAX_LINES`: The maximum number of lines you can bet on.
- `MAX_BET`: The maximum amount you can bet on each line.
- `MIN_BET`: The minimum amount you can bet on each line.
- `ROWS`: The number of rows in the slot machine.
- `COLS`: The number of columns in the slot machine.
- `symbol_count`: A dictionary that maps symbols to the number of times they appear in the slot machine.
- `symbol_value`: A dictionary that maps symbols to their corresponding payout.
