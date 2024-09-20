# World-s-Real-Time-clock-Chrome-extensionn

Real Time Clock with Country Timezone Selection
This project is a real-time clock application that allows users to view the current time for different countries around the world. It features both a digital clock and an analog clock that update dynamically based on the selected country from the dropdown menu. The clock is synced using timezone offsets from the World Time API and smoothly displays the time without excessive API calls.

Features
Real-time digital clock that displays the current time.
Analog clock with moving hour, minute, and second hands.
Dropdown menu for selecting timezones from a list of countries.
Automatically sets the default timezone to India (Asia/Kolkata).
A smooth background animation with a gradient effect.
Technologies Used
HTML: Structure of the page.
CSS: Styles for the page, including the clock face, clock hands, and background animation.
JavaScript: Handles time fetching, updating the clocks, and managing timezones.
Project Setup
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/real-time-clock.git
cd real-time-clock
Open the project in your browser:

You can directly open the index.html file in your browser.
Test the functionality:

Select different countries from the dropdown menu to see the time update accordingly.
How It Works
The project fetches the current time from the World Time API for the selected timezone using a dropdown menu.
The digital clock updates every second to show the current local time for the selected country.
The analog clock is synchronized to match the digital time, with the hands rotating to reflect the correct hour, minute, and second positions.
The background animation uses a CSS gradient that transitions smoothly between different colors.
Files
index.html: Main HTML file containing the clock and country selection dropdown.
styles.css: Internal CSS used to style the clocks and the background.
script.js: JavaScript used to fetch time data and update the clocks.
Future Improvements
Add more customization options, like 24-hour vs 12-hour clock.
Add more countries or regions to the dropdown menu.
Provide offline support for the clock using the user's local time when the API is unavailable.
