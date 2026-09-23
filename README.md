# Project Name
It is simple delivery fee calculator when a user wants to know the total order cost based on the day of the week.
## Setup
```bash
# Activate conda environment
conda activate aigc5005
## Run
lab01b.ipynb
## Example
Enter the delivery day (e.g. Monday): Monday
Enter the amount of order (e.g. 50): 50
Your order amount is 50. The delivery fee for Monday is 5. Your total amount to pay is 55.
## Known limitations
- Single-line input not supported: Date and delivery fee must be entered separately rather than in a single line.
- Date picker would be better to input for users
- No input retry loop: When invalid input is entered, the program raises a SystemExit and terminates immediately instead of asking the user to re-enter the value.
