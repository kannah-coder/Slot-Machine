 # Slot Machine Game (Python)

This is a simple command-line slot machine game built in Python. The player can deposit money, choose the number of lines to bet on, place bets, and spin the slot machine to try and win.

## Features
- Deposit money before playing.
- Bet on up to 3 lines.
- Set a custom bet per line (within limits).
- Randomized slot machine symbols with different values and probabilities.
- Calculates winnings based on matching symbols across lines.
- Updates player balance after each spin.

## Rules
- Minimum bet: $1  
- Maximum bet: $100  
- Maximum lines: 3  
- Symbols have different counts and payout values:
  - **A** → Highest payout (value 5, rarest)  
  - **B** → Value 4  
  - **C** → Value 3  
  - **D** → Lowest payout (value 2, most common)  

## How to Run
1. Make sure you have Python 3 installed.  
2. Save the code into a file named `slot_machine.py`.  
3. Open a terminal in the project folder.  
4. Run the game:
   ```bash
   python slot_machine.py
   
   
