## Currency-Converter

## Overview

The Currency Converter is a web application that allows users to convert between different currencies using real-time exchange rates fetched from the Fixer.io API. This application features a modern, futuristic design with animated backgrounds and interactive elements, providing an engaging user experience.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [API Integration](#api-integration)
- [Credits](#credits)
- [License](#license)

## Features

- **Real-time Currency Conversion**: Fetches the latest exchange rates from the Fixer.io API.
- **Futuristic Design**: Includes a floating planet background image with smooth animations.
- **Responsive UI**: The design adapts to different screen sizes, providing a consistent experience across devices.
- **Interactive Elements**: Includes hover effects and animations that enhance the user experience.
- **Customizable**: Easily change the background, colors, and animations to fit your brand or style.

## Technologies Used

- **HTML5**: For structuring the webpage.
- **CSS3**: For styling the webpage and adding animations.
- **JavaScript (ES6)**: For interacting with the Fixer.io API and handling currency conversions.
- **Fixer.io API**: To fetch real-time exchange rates.

## Installation

### Prerequisites
- A modern web browser (Google Chrome, Mozilla Firefox, etc.)
- A text editor or IDE (Visual Studio Code, Sublime Text, etc.)

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/xrishis/currency-converter.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd futuristic-currency-converter
   ```
3. **Open the Project**:
   - You can open the `index.html` file in your browser directly by double-clicking it, or
   - Open the project in your preferred text editor for further customization.

## Usage

### Running the Application
- Open the `index.html` file in your web browser.
- Enter the amount you wish to convert.
- Select the currencies you want to convert from and to using the dropdowns.
- Click the "Convert" button to see the result.

### Customizing API Key
- Replace the `apiKey` in the JavaScript section of `index.html` with your Fixer.io API key:
  ```javascript
  const apiKey = 'your_api_key_here';  // Your Fixer.io API key
  ```

## Project Structure

```plaintext
futuristic-currency-converter/
│
├── index.html         # The main HTML file that contains the structure of the webpage
├── style.css          # The CSS file containing styles and animations for the webpage
├── script.js          # The JavaScript file handling API requests and currency conversions
├── README.md          # This README file
└── assets/
    └── planet.png     # The image file used for the background animation
```

### Key Files
- **index.html**: The main HTML file that includes the structure of the webpage and inline CSS/JS for easy modification.
- **style.css**: Contains all the styles, including the background animations, color schemes, and responsive design.
- **script.js**: Handles fetching data from the Fixer.io API and performing the currency conversion calculations.

## Customization

### Background Image
- The background image (`planet.png`) is located in the `assets/` directory. You can replace it with any image of your choice by updating the `src` attribute in the `index.html` file:
  ```html
  <img class="planetImg" src="assets/planet.png" alt="Background Image">
  ```

### Colors and Animations
- Modify the `style.css` file to change the colors and animations. For instance, you can adjust the animation speed or background color to match your design preferences.

### Dropdown List Styling
- The dropdown list colors can be customized in the `style.css`:
  ```css
  select {
      background-color: rgba(255, 182, 193, 0.8); /* Light pink background */
      color: black;
  }
  ```

## API Integration

This project uses the Fixer.io API to fetch the latest exchange rates. Ensure that your API key is active and correctly implemented in the `index.html` file. The API URL is structured as follows:

```javascript
const apiUrl = `http://data.fixer.io/api/latest?access_key=${apiKey}`;
```

## Credits

- **Design Inspiration**: The futuristic design elements were inspired by modern web design practices and specifically tailored for a sleek, immersive experience.
- **Background Image**: The floating planet image was sourced from the NTP website example provided.
- **API Service**: The Fixer.io API is used to provide real-time currency exchange rates.

## Link 
https://xrishis.github.io/Currency-Converter/

## License

This project is licensed under the MIT License.
