# OOP Coffee Machine

A Python-based command-line Coffee Machine simulator built using Object-Oriented Programming (OOP) principles. The program handles inventory tracking, menu selection, coin processing, and transaction management across modular Python classes.

## Features

* **Interactive Menu:** Dynamically displays available drinks and retrieves pricing/ingredient details.
* **Resource Management:** Tracks water, milk, and coffee levels, ensuring orders only proceed if sufficient ingredients exist.
* **Payment Processing:** Accepts standard coin denominations (quarters, dimes, nickels, pennies), calculates totals, and handles change or refunds.
* **Administrative Commands:** 
  * `report`: Displays current resource levels and total profits.
  * `off`: Powers down the machine execution loop.

## File Structure

* `main.py` - Primary application entry point controlling the main loop and logic flow.
* `menu.py` - Defines `Menu` and `MenuItem` classes to manage available beverages.
* `coffee_maker.py` - Handles inventory resources and beverage preparation.
* `money_machine.py` - Manages coin insertion, payment verification, and profit logging.

## Requirements

* Python 3.x

## How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/coffee-machine-oop.git](https://github.com/your-username/coffee-machine-oop.git)
   cd coffee-machine-oop
