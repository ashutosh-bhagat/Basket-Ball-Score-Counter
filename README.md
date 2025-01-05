# Basketball Score Counter Webpage

### Overview

The Basketball Score Counter is a simple and interactive webpage that allows users to keep track of scores for two teams: Home and Guest. It also includes a reset functionality to clear the scores and start over.

This project is implemented using HTML, CSS, SCSS, and JavaScript.

<br>


## Features

1. Home and Guest Counters

Functionality:

Each team has its own counter displayed prominently on the webpage.

Users can increase the score for each team by clicking the respective buttons.

Design:

Counters are visually distinct and labeled for clarity ("Home" and "Guest").

2. Increment Buttons

Functionality:

Buttons allow users to add points to the respective team's score.

Points can be incremented by 1, 2, or 3 for each team, depending on the button clicked.

Implementation:

Each button triggers a JavaScript function that updates the displayed score dynamically.

3. Reset Button

Functionality:

Clicking the reset button sets both counters (Home and Guest) back to zero.

Implementation:

The reset functionality is implemented using a JavaScript function that resets the score values and updates the display.


<br>
## Technologies Used

1. HTML

Provides the structure of the webpage, including elements for counters, buttons, and labels.

2. CSS

Used for basic styling of the webpage elements like fonts, colors, and layout.

3. SCSS

Enables the use of variables, nesting, and mixins to create a more organized and maintainable stylesheet.

SCSS is compiled into CSS to style the webpage.

4. JavaScript

Handles the interactive functionality of the counters and reset button.

Dynamically updates the DOM based on user interactions.

<br>

### File Structure

Basketball-Score-Counter/ <br>
|-- index.html        # HTML file for the webpage structure <br>
|-- style.css         # Compiled CSS file for styling<br>
|-- style.scss        # SCSS file for advanced styling features<br>
|-- script.js         # JavaScript file for interactivity<br>


<br>

## How to Use

Open the index.html file in any modern web browser.

Use the buttons under the "Home" and "Guest" counters to add points to the respective teams.

Buttons will add 1, 2, or 3 points per click.

Click the "Reset" button to clear both scores and start over.

Future Enhancements

Add animations or visual effects when scores are updated.

Allow users to set custom team names.

Include a timer to track game duration.

Implement responsive design for better mobile compatibility.

License

This project is open-source and available under the MIT License. Feel free to use and modify it as per your requirements.

Author

Created by Ashutosh Bhagat.
