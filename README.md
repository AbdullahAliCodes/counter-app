# Passenger Counter App

A simple and efficient web application designed to track and record the number of people entering a location, such as a subway station or a bus. This tool allows users to increment a counter and save the entries into a persistent log on the screen.

## Live Demo

You can view and use the live application here: [https://counter-12345.netlify.app/](https://counter-12345.netlify.app/)

## Features

- **Real-time Counting**: An "Increment" button that increases the count by one with every click.
- **Save Functionality**: A "Save" button that logs the current count and displays it in a "Previous entries" section.
- **Visual Feedback**: The current count is displayed prominently in a large, easy-to-read format.
- **Themed Background**: Features a subway/station-themed background image for a specific use-case feel.

## Technology Stack

- **HTML5**: Used for the structural layout of the counter and buttons.
- **CSS3**: Provides the styling, including background image handling and button layout.
- **JavaScript**: Powers the core logic for the increment and save functions, as well as DOM manipulation to update the screen.

## How to Run Locally

This is a client-side application that runs entirely in your web browser.

1. Download or clone the repository to your local machine.
2. Ensure the `station.jpg` file is in the same folder as your code files for the background to display correctly.
3. Open the `index.html` file in your preferred web browser.

## Usage Instructions

1. Click the **INCREMENT** button to count each person as they enter.
2. Click the **SAVE** button to record the current number into the log below.
3. After saving, the counter will automatically reset to 0 for the next batch of entries.
