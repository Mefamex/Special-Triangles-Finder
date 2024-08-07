# Special-Triangles-Finder

This Python script contains a class (`SpeTriFinder`) that finds special triangles based on the user-provided X and Y values.
Formula: Pythagorean Theorem: `|x² - y²|` and `2xy` and `x² + y²`

## Description

In this project, there is a Python class (`SpeTriFinder`) that finds special triangles based on the X and Y values provided by ⁸the user. Triangles are calculated using the Pythagorean theorem and minimized to their smallest form.

## Requirements

The following dependencies are required to run the project:

- Python 3.x


## Installation

1. **Download the Project:**
   - To download the project, open your terminal or command prompt and run the following command:
     ```bash
     git clone https://github.com/Mefamex/Special-Triangles-Finder.git
     ```

2. **Change to Project Directory:**
   - Change to the directory of the downloaded project by running the following command in your terminal or command prompt:
     ```bash
     cd Special-Triangles-Finder
     ```

3. **Run the Script:**
   - To run the script, enter the following command in your terminal or command prompt:
     ```bash
     python main.py

## How to Use

You can use the `SpeTriFinder` class by using the `main.py` file in the project.

```python
# Example Usage
from main import SpeTriFinder

# User-provided X and Y values
user_X = 10
user_Y = 10

# Create a SpeTriFinder instance
finder = SpeTriFinder(user_X, user_Y)

# or
finder.run_finder(5, 5, show=False)

# or 
SpeTriFinder(3, 3)

# or
big = SpeTriFinder(100, 100, False)
print(big.spec_tri[-1])
```

## Examples' Results

### Example 1:
```plaintext
max values and side: 10, 10, 200
18 special triangles found
[3, 4, 5]
[5, 12, 13]
[7, 24, 25]
[8, 15, 17]
[9, 40, 41]
[11, 60, 61]
[12, 35, 37]
[13, 84, 85]
[15, 112, 113]
[16, 63, 65]
[17, 144, 145]
[20, 21, 29]
[28, 45, 53]
[33, 56, 65]
[36, 77, 85]
[39, 80, 89]
[48, 55, 73]
[65, 72, 97]
Done!  ---------------
```

### Example 2:
```plaintext
max values and side: 5, 5, 50
4 special triangles found
[3, 4, 5]
[5, 12, 13]
[7, 24, 25]
[8, 15, 17]
Done!  ---------------
```
