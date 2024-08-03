# Screenshot Screenshotter

## Description

Screenshot Screenshotter is a web application that allows users to capture high-quality screenshots of websites using the ApiFlash API. This app enables users to enter a URL and specify various parameters to customize the screenshots. The main features include making API calls to capture screenshots, displaying the current screenshot, and maintaining a gallery of all screenshots taken.

## Features

- **Capture Screenshot:** Users can input a URL and other parameters to capture a screenshot of the specified website.
- **Screenshot Display:** Shows the latest screenshot on the page.
- **Screenshot Gallery:** Displays all the screenshots taken by the user in a gallery format.
- **API Query Status:** Displays whether the app has hit the maximum number of API queries allowed.

## Technologies Used

- **React:** For building the user interface and managing application state.
- **HTML/CSS:** For structuring and styling the application.
- **JavaScript:** For handling API interactions and dynamic content updates.
- **ApiFlash API:** For generating screenshots of web pages.

## How It Works

1. **Capture Screenshot:**
   - Users input a URL and configure parameters for the screenshot (e.g., format, dimensions).
   - Upon submission, an API call is made to ApiFlash to capture the screenshot.
   - The resulting screenshot is displayed on the page.

2. **Gallery of Screenshots:**
   - All screenshots captured during the session are saved and displayed in a gallery format.

3. **API Query Status:**
   - The app checks the remaining number of allowed API queries and displays this information to the user.

4. **Interactive Elements:**
   - Users can see the results of their queries in real-time with updates to the displayed screenshot and gallery.

## Goals

By the end of this project, you will be able to:

- Make a static API call using `async/await` and save the results to a state variable.
- Add and edit query parameters for API calls.
- Display the screenshot returned by the ApiFlash API on the page.
- Maintain a gallery of all screenshots queried thus far.
- Track and display whether the app has hit the maximum number of allowed API queries.

## Demo

Explore an example of what you'll be building in this lab:

![Video Walkthrough](https://github.com/vetskiver/cap/blob/master/cap-demo.gif)

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/screenshot-screenshotter.git
