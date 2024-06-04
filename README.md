# Dice Roller

This is a simple Python program that simulates rolling a specified number of dice and prints their results using ASCII art. The program also calculates and displays the total sum of the rolled dice.

## Features

1. **Dice Rolling**: Simulates rolling a specified number of dice.
2. **ASCII Art Representation**: Displays the result of each die roll using ASCII art.
3. **Total Calculation**: Calculates and prints the total sum of the rolled dice.

## How to Use

1. **Run the Program**: Execute the Python script.
2. **Input the Number of Dice**: Enter the number of dice you want to roll when prompted.
3. **View Results**: The program will display each die's result in ASCII art and the total sum of all dice rolled.

## Code Explanation

### Variables

- `dice_art`: A dictionary containing the ASCII art for dice faces from 1 to 6.
- `dice`: A list to store the results of each die roll.
- `total`: A variable to keep track of the total sum of the rolled dice.
- `num_of_dice`: The number of dice the user wants to roll.

### Logic

1. **Input**: The user is prompted to enter the number of dice to roll.
2. **Rolling Dice**: The program rolls the specified number of dice and stores the results in the `dice` list.
3. **Displaying Results**: The results are displayed using ASCII art.
4. **Calculating Total**: The total sum of the rolled dice is calculated and printed.

### Dice Rolling and Display

The program generates random numbers between 1 and 6 to simulate rolling dice. It uses the `random.randint(1, 6)` function for this purpose. The results are then displayed using the corresponding ASCII art from the `dice_art` dictionary.

### Vertical and Horizontal Display

The program currently prints the dice results vertically. However, it includes commented-out code that can be used to print the results horizontally.

### Example

Here's a step-by-step example of using the Dice Roller:

1. Run the script.
2. Enter the number of dice (e.g., `3`).
3. View the dice results displayed in ASCII art:
    ```
    ┌─────────┐
    │  ●      │
    │         │
    │      ●  │
    └─────────┘
    ┌─────────┐
    │  ●   ●  │
    │  ●   ●  │
    │  ●   ●  │
    └─────────┘
    ┌─────────┐
    │  ●      │
    │    ●    │
    │      ●  │
    └─────────┘
    ```
4. The total sum is printed, e.g., `total: 11 out of 18`.

## Requirements

- Python 3.x

## Running the Program

1. Ensure you have Python installed on your machine.
2. Save the code to a file, e.g., `dice_roller.py`.
3. Run the script using `python dice_roller.py`.

## Author

- Developed by: PavanTeja-777

## License

- This program is for educational and entertainment purposes. Feel free to modify and enhance it.

Enjoy rolling the dice! If you have any questions or feedback, feel free to reach out.
