# Grade Calculator

This is a Flask-based web application that helps students calculate the minimum midterm and final grades required to pass a subject. The program takes the preliminary grade as input, validates it, and determines if passing the subject is possible. If it is possible, the program computes the minimum grades needed for midterms and finals.

## Features

- Accepts a preliminary grade and calculates the required Midterm and Final grades to pass the subject.
- Validates that the input is a valid number between 0 and 100.
- Displays meaningful error messages when input is invalid.
- Provides feedback if it is impossible to pass based on the preliminary grade.
- Simple and intuitive web interface using Flask.

## Grade Composition

- **Prelim Grade**: 20% of the overall grade
- **Midterm Grade**: 30% of the overall grade
- **Final Grade**: 50% of the overall grade
- **Passing Grade**: 75

## Requirements

To run this application, you will need:

- **Python** (version 3.6 or higher)
- **Flask** (Python web framework)

## Installation

1. Clone this repository.
2. Install Flask:
   ```bash
   pip install Flask
