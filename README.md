# gca-personalized-destinations
## Portfolio Project: Marriott Bonvoy Hotels and Villas

## Overview
This project is part of the Global Career Accelerator (GCA) program. It is an interactive destination recommendation tool that asks users for their preferred destination type (city, beach, or mountains) and then displays a list of tailored travel recommendations based on their selection. The project was implemented with vanilla JavaScript and integrates with an interactive map.

## Prototype and Research
Before coding, I developed an early interactive prototype in Google Slides to map out user flows and destination selection ideas.  
👉 [View the prototype here](LINK_HERE)

For more details about my market research and user considerations, check out [marketUsersPrototype.md](./marketUsersPrototype.md).

## My Contributions
I was responsible for the development of script.js JavaScript logic, which includes:

1. **Filtering Places by Type:**  
   Users' preferences (city, beach, or mountain) are used to filter a large array of destination data, providing them with a personalized list of recommendations.

2. **Generating Destination Cards:**  
   A dynamic card is created for each destination using DOM manipulation, which showcases the destination's name, location, and an image.

3. **Populating the Recommendations Section:**  
   The filtered places are dynamically added to the recommendations section as cards, ensuring that the user gets relevant suggestions based on their preference.


## Features
- **Modal Popup:**  
  On page load, a modal asks users whether they want to go to a city, beach, or mountain destination.
  
- **Filtered Recommendations:**  
  Depending on the user's selection, the app displays destinations that match their preference.

- **Interactive Map:**  
  Clicking on any recommendation will zoom in on the location on the map.

## Technologies Used
- JavaScript
- HTML/CSS
- Bootstrap 
- Open Layers API (for map integration)

## How to Run the Project Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/gca-personalized-destinations.git
    ```
2. Navigate to the project directory:
    ```bash
    cd gca-personalized-destinations
    ```
3. Open `index.html` in your browser to view the project.

## Files Overview

- **index.html**: The main HTML structure and layout of the page.
- **style.css**: The custom CSS for styling the webpage.
- **script.js**: Contains all JavaScript code responsible for the logic behind the destination selection and rendering.
- **places.js**: Contains the array of place objects used for filtering and display.

## Acknowledgments
- The initial concept and structure of this project were based on the Global Career Accelerator program's assignment. 
