# **Chair Number Game**

This Python script is a simple game where the user enters a chair number, and if the number matches a specific winning number, they win.

**Usage :**

1. Run the script.
2. Enter your chair number when prompted.

The script will then check if the chair number matches the winning number and display the result.

**Example :**

If you enter:
- Chair number: 21

The script will output:
- You win

If you enter a different number, it will output:
- Sorry

**Exclude a Specific Number**

If you want to exclude a specific number from winning, such as 13, you can uncomment the code block below and modify the logic as follows:

```python
chair_number = int(input("Enter your chair number: \n"))
if chair_number != 13:
    print("You win")
else:
    print("Sorry")
