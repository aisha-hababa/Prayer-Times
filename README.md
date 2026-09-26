🕌 Prayer Times

A modern and responsive Prayer Times web application built with HTML, CSS, and JavaScript.

The app allows users to get accurate daily prayer times based on their location, city, country, and selected date.

## ✨ Features

- 🕌 Display the five daily prayer times:
  - Fajr
  - Dhuhr
  - Asr
  - Maghrib
  - Isha
- ⏰ Display the next prayer
- 📅 Select a specific date
- 🌍 Search prayer times by city and country
- 📍 Automatically detect the user's location
- 🔄 Automatically load prayer times based on the detected location
- 🌐 Reverse geocoding to determine the user's city and country
- 📱 Responsive and user-friendly interface
- 🎨 Modern card-based UI
- ✨ Smooth hover effects and visual interactions
- ⚡ Dynamic data fetched from an external API

## 🛠️ Technologies Used

- **HTML5** — Application structure
- **CSS3** — Responsive design, gradients, cards, shadows, and animations
- **JavaScript (ES6)** — API requests, DOM manipulation, location detection, and dynamic content
- **AlAdhan API** — Prayer times data
- **OpenStreetMap Nominatim** — Reverse geocoding and location information

## 🌐 APIs

### AlAdhan API

The application uses the AlAdhan API to retrieve prayer times based on the selected date, city, and country.

```text
https://api.aladhan.com/v1
OpenStreetMap Nominatim

Nominatim is used for reverse geocoding to convert the user's geographic coordinates into location information such as city and country.

📂 Project Structure
Prayer-Times/
│
├── index.html
└── README.md

The current version of the project contains the HTML, CSS, and JavaScript code inside a single index.html file.

🚀 Getting Started
1. Clone the repository
git clone https://github.com/aisha-hababa/Prayer-Times.git
2. Open the project
cd Prayer-Times
3. Run the application

Open index.html directly in your browser.

You can also use the Live Server extension in VS Code for development.

📍 Location Detection

When the application opens, it requests the user's browser location permission.

If permission is granted, the application:

Gets the user's latitude and longitude.
Uses reverse geocoding to identify the city and country.
Fills the location fields automatically.
Fetches the prayer times for the current date.
🎯 Project Purpose

This project was created as a frontend development project to practice working with external APIs, asynchronous JavaScript, browser geolocation, and dynamic user interfaces.

The project focuses on:

API integration
Fetch API
Async/Await
DOM manipulation
Browser Geolocation API
Reverse geocoding
Dynamic content rendering
Responsive web design
Error handling
Building clean and interactive interfaces
🔮 Future Improvements
 Add a countdown timer for the next prayer
 Add prayer notifications
 Add multiple calculation methods
 Add a dark mode
 Add Hijri date
 Add monthly prayer timetable
 Improve mobile responsiveness
 Add language selection
 Save the user's preferred location
 Separate HTML, CSS, and JavaScript into dedicated files
📸 Preview

Add a screenshot of the application here.

👩‍💻 Author

Aisha Hababa

Software Engineering Graduate

Frontend Development • UI/UX Design

🔗 Repository

View Prayer Times on GitHub
