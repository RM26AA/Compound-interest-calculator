# Compound Interest Calculator

## Overview
The Compound Interest Calculator is a web-based application that allows users to calculate their future savings based on compound interest. Using an intuitive interface, users can input values such as starting balance, annual interest rate, contribution, and the compounding frequency to see their savings grow over time. The application visualizes the results using a bar chart powered by Chart.js.

## Features
- **Dynamic Calculations**: Computes total savings using the compound interest formula:
  \[
  A = P(1 + r/n)^{nt} + PMT \frac{(1 + r/n)^{nt} - 1}{r/n}
  \]
- **User-Friendly Input**: Allows users to enter details like starting balance, interest rate, contributions, and compounding frequency.
- **Interactive Visualization**: Displays a bar chart comparing savings with and without interest using Chart.js.
- **Responsive Design**: A clean and responsive interface optimized for various devices.

## Technologies Used
- **HTML**: Structures the web interface for inputs and results display.
- **CSS**: Styles the calculator, ensuring a professional and user-friendly layout.
- **JavaScript**: Handles the compound interest calculations and updates the visualization dynamically.
- **Chart.js**: Creates the interactive bar chart to compare results visually.

## Files
- **index.html**: Contains the structure of the calculator, including input fields and a canvas for the chart.
- **style.css**: Defines the styling for the calculator interface, ensuring a clean and responsive design.
- **interest_calculator.js**: Implements the calculation logic and integrates Chart.js for data visualization.

## External Libraries
- **Chart.js**: The library used for creating dynamic bar charts. Documentation is available [here](https://www.chartjs.org/docs/latest/getting-started/)&#8203;:contentReference[oaicite:0]{index=0}.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository-name.git
2. Navigate to the project directory:
   ```bash
   cd your-repository-name
3. Open the index.html file in any modern web browser to start using the calculator.

## How to Use
- Enter the starting balance, contribution, interest rate, years, and compounding frequency.
- Click the Calculate button.
- View the total savings with and without interest and a bar chart for comparison.

## License:
This project is open-source and available under the MIT License.

## Author:
Romeo Maunick - A developer dedicated to creating intuitive financial tools and interactive web applications.



















