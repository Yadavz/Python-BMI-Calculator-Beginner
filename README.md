# Body Mass Index (BMI) Calculator

This is a Python program that calculates a person's BMI based on their weight and height. BMI is a measure of body fat and is widely used as a screening tool to identify potential health problems. This project allows users to input their weight and height, and calculates their BMI using the formula (weight in pounds * 703) / (height in inches * height in inches).

## Requirements

To use the BMI Calculator, the user needs to have Python 3 installed on their system.

## Usage

To use the BMI Calculator, the user needs to run the program in the command line and enter their name, weight in pounds, and height in inches when prompted. The program then calculates the user's BMI and prints a message indicating their weight status based on established BMI ranges.

For example, to use the BMI Calculator, the user can run the following command:

```
python bmi_calculator.py
```

The program will prompt the user to enter their name, weight, and height in pounds and inches respectively. After entering this information, the program will calculate the user's BMI and print a message indicating their weight status.

## Benefits

This project demonstrates proficiency in using Python to perform simple calculations and generate clear and informative output. It is a useful tool for anyone who wants to quickly and easily calculate their BMI and assess their overall health status. The BMI ranges used in the program are based on established guidelines from the World Health Organization (WHO), which are widely recognized and accepted.

## Implementation Details

The program starts by prompting the user to enter their name, weight, and height in pounds and inches respectively. It then calculates the BMI using the formula (weight in pounds * 703) / (height in inches * height in inches).

After calculating the BMI, the program prints a message indicating the user's weight status based on established BMI ranges. The weight status categories used in the program are:

- Underweight: BMI < 18.5
- Normal weight: 18.5 <= BMI < 25
- Overweight: 25 <= BMI < 30
- Obese: 30 <= BMI < 35
- Severely obese: 35 <= BMI < 40
- Morbidly obese: BMI >= 40

Overall, this program provides a simple and effective way to calculate and assess BMI using Python. It is user-friendly and generates clear and informative output that can help users assess their overall health status.

