📘 Project Overview

Weather Now is a responsive web application that allows users to quickly check the current weather conditions for any city in the world.
This project was created as part of the Aganitha Full Stack Developer Take-Home Challenge to demonstrate UI development, API integration, and clean coding practices.

🎯 Objective

To build a simple, user-friendly, and functional weather app using React and a public API — following the guidelines provided in the challenge PDF.

🧰 Tech Stack

Frontend Framework: React (via CodeSandbox)

Styling: Inline CSS (simple and responsive)

API Used: Open-Meteo API

Geocoding API: Open-Meteo Geocoding API

Hosting: CodeSandbox

Language: JavaScript (ES6+)

⚙️ How It Works

The user enters a city name.

The app calls the Geocoding API to get the city’s latitude and longitude.

Then it fetches current weather data (temperature, windspeed, and time) from the Open-Meteo API.

Results are displayed in a clean, readable format.

If no city is found, an error message is shown.

🚀 Features

✅ Search weather by city name
✅ Displays temperature, wind speed, and local time
✅ Handles invalid input and API errors
✅ Clean and minimal UI
✅ Responsive layout for desktop and mobile

🧠 Learning & Approach

Followed the problem statement from the official PDF.

Used ChatGPT for brainstorming, debugging, and code improvement.

Focused on clarity, readability, and error handling.

Deployed on CodeSandbox for easy public access.

🖥️ Demo

🔗 Live Demo: https://codesandbox.io/p/sandbox/3k9h97

⚠️ Error Handling

If the user enters an invalid city, a message “City not found. Please try again.” is displayed.

If the API call fails, a general error “Error fetching weather data.” is shown.

🕒 Future Improvements (Optional)

🌍 Auto-detect location using browser geolocation

🌦️ Add weather icons (sun, cloud, rain, etc.)

💾 Save recent searches in localStorage

🎨 Improve design with Tailwind CSS# weather-now-project
Created with CodeSandbox
