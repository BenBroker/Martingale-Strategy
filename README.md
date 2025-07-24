# Martingale Strategy Simulation in Roulette

This project simulates using the classic Martingale betting strategy at a roulette table — where you double your bet after each loss until you either win back your money, double your wealth, or go broke. It’s a simple system with a dangerous flaw: if you lose too many times in a row, you're out.

---

# Why I Built This

I had some debates with my friends... even one of their dads. They all claimed that this was a guarentee to win infinite money. Yet all of their stories involved them unluckily losing 8 roulette spins in a row. 

This simulation gets to the bottom of the Martingale strategy.

---

# What It Does

- Simulates roulette spins using a simplified European wheel (1–36 red/black, 1 green zero)
- Bets only on red, with the Martingale strategy:
  - Double the bet after every loss
  - Return to original bet after a win
- Tracks your total wealth over time
- Repeats this simulation thousands of times to see long-term outcomes
- Visualizes your wealth over spins
- Calculates the success rate and average time to double your money

---
# How To Customize

Enter your custom values! You can also easily change the code to stop at a win of 5x your money or a simple $100 profit!
