# Unit Conversion Calculator

## Overview

This is a single-file, browser-based Unit Conversion Calculator built using React and Tailwind CSS. It allows users to convert between various units across multiple categories, including:

- **Currency**: United States Dollar (USD), Euro (EUR), British Pound (GBP), Japanese Yen (JPY), Indian Rupee (INR), Australian Dollar (AUD), Canadian Dollar (CAD), Swiss Franc (CHF), Chinese Yuan (CNY), New Zealand Dollar (NZD), Singapore Dollar (SGD), Brazilian Real (BRL)
- **Length**: Meter (m), Kilometer (km), Centimeter (cm), Millimeter (mm), Foot (ft), Inch (in), Mile (mi)
- **Area**: Square Meter (sqm), Square Kilometer (sqkm), Square Centimeter (sqcm), Square Foot (sqft), Square Mile (sqmi), Acre (acre)
- **Speed**: Meter per Second (mps), Kilometer per Hour (kmph), Mile per Hour (mph), Knot (knot)
- **Temperature**: Celsius (C), Fahrenheit (F), Kelvin (K)
- **Power**: Watt (W), Kilowatt (kW), Megawatt (MW), Horsepower (hp)
- **Pressure**: Pascal (Pa), Kilopascal (kPa), Bar (bar), Pound per Square Inch (psi), Atmosphere (atm)
- **Weight**: Kilogram (kg), Gram (g), Milligram (mg), Pound (lb), Ounce (oz), Metric Ton (t)

The application features a clean, responsive user interface and supports real-time conversions with error handling for invalid inputs.

## Features

- **Responsive Design**: Built with Tailwind CSS, the UI adapts to various screen sizes, from mobile to desktop.
- **Multiple Categories**: Supports conversions across eight categories with comprehensive unit options.
- **Real-time Conversion**: Updates results instantly as users type or change units.
- **Temperature Handling**: Special logic for non-linear temperature conversions (Celsius, Fahrenheit, Kelvin).
- **Error Handling**: Prevents crashes with checks for invalid inputs or undefined units.
- **Extensible**: Conversion factors are stored in a structured JavaScript object, making it easy to add new units or categories.
- **Full Unit Names**: Displays full names (e.g., "United States Dollar" for USD) for clarity.

## Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Safari, Edge).
- No additional software or server setup is required, as the application runs entirely in the browser using CDN-hosted libraries.

## Setup and Usage

1. **Save the File**:
   - Copy the HTML code into a file named `index.html`.
   - Ensure you have an internet connection, as the application relies on CDN-hosted libraries (React, ReactDOM, Babel, Tailwind CSS).

2. **Open in Browser**:
   - Open `index.html` in a web browser by double-clicking the file or dragging it into the browser window.
   - Alternatively, serve it using a local server (e.g., with Python: `python -m http.server 8000`) and navigate to `http://localhost:8000`.

3. **Using the Calculator**:
   - **Select a Category**: Choose a conversion category (e.g., Currency, Length) from the dropdown menu.
   - **Enter a Value**: Input a numeric value in the "From" field.
   - **Select Units**: Choose the source and target units from the respective dropdowns.
   - **View Results**: The converted value appears instantly below, formatted as "[input] [source unit] = [result] [target unit]".
   - If the source and target units are the same, a message indicates this.
   - If no value is entered, a prompt to "Enter a value to convert" is displayed.

## Example

- **Convert 100 USD to EUR**:
  - Select "Currency" from the category dropdown.
  - Enter `100` in the input field.
  - Choose "United States Dollar (USD)" as the "From" unit.
  - Choose "Euro (EUR)" as the "To" unit.
  - Result: `100 United States Dollar = 92 Euro` (based on the static rate of 0.92).

- **Convert 25 Celsius to Fahrenheit**:
  - Select "Temperature" from the category dropdown.
  - Enter `25` in the input field.
  - Choose "Celsius (C)" as the "From" unit.
  - Choose "Fahrenheit (F)" as the "To" unit.
  - Result: `25 Celsius = 77 Fahrenheit`.

## Notes

- **Currency Rates**: The currency conversion rates are static and approximate (as of May 26, 2025). For real-time rates, integrate an API like `exchangeratesapi.io` by modifying the JavaScript code to fetch live data.
- **Limitations**: The application runs in a single HTML file, which limits its scalability. For a production environment, consider converting it to a full React application with a build tool like Vite (see alternative implementation).
- **Extensibility**: To add more units, update the `conversionFactors` object in the JavaScript code. For example, to add a new currency, include it in the `currency.units` object with its full name and conversion factor relative to USD.
- **Error Handling**: The application handles invalid inputs and same-unit conversions gracefully, logging errors to the console if they occur.



## Future Improvements

- Add a "Swap" button to switch source and target units.
- Integrate a live currency API for real-time exchange rates.
- Add a history feature to track recent conversions.
- Convert to a full React application with TypeScript and Vite for better scalability and development experience.



# Badges

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)






## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/achyuth-kumar-698105325)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://x.com/Achyuth88344725?t=aQNkQOXmCNs4581HVgKvzg&s=09)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:achyuthk865@gmail.com)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/achyuth_kumar85/)
