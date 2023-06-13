# Bidding App

This is a simple Python script that allows users to participate in a bidding process. The script imports a logo and clears the console screen before prompting users for their name and bid amount. The bidding process continues until there are no more bidders, and the script determines the highest bidder.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/herambbp/secret_auction.git
   ```

2. Navigate to the project directory:
   ```
   cd secret_auction
   ```

3. Run the script:
   ```
   python secret_auction.py
   ```

## Usage

1. Run the script in a Python environment.

2. Enter your name when prompted.

3. Enter your bid amount.

4. If there are more bidders, type 'yes' to continue. Otherwise, type 'no' to finish the bidding process.

5. Once the bidding process is finished, the script will display the winner's name and bid amount.

## Output

```
$ python bidding_app.py

                         ___________
                         \         /
                          )_______(
                          |"""""""|_.-._,.---------.,_.-._
                          |       | | |               | | ''-.
                          |       |_| |_             _| |_..-'
                          |_______| '-' `'---------'` '-'
                          )"""""""(
                         /_________\\
                       .-------------.
                      /_______________\\
                      
What is your name?: John
What is your bid? $100
Are there any other bidders? Type 'yes' or 'no'.
yes

                         ___________
                         \         /
                          )_______(
                          |"""""""|_.-._,.---------.,_.-._
                          |       | | |               | | ''-.
                          |       |_| |_             _| |_..-'
                          |_______| '-' `'---------'` '-'
                          )"""""""(
                         /_________\\
                       .-------------.
                      /_______________\\
                      
What is your name?: Sarah
What is your bid? $150
Are there any other bidders? Type 'yes' or 'no'.
no

The winner is Sarah with a bid of $150
```
