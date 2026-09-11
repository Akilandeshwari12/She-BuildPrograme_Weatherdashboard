# 🌤️ Weather Dashboard Application

A simple and responsive **Weather Dashboard Application** that allows users to search for any city and view its current weather conditions using a public weather API.

## 📌 Features

* Search weather by city name
*  Display current temperature
* Display weather condition and weather icon
* Display feels-like temperature
* Display humidity
* Display wind speed
* Display rainfall information
* Store and display recent searches
* Click recent searches to view weather again
* Clear recent search history
* Error handling for invalid city names
* Search using the Enter key
* Responsive design for desktop and mobile devices

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* Fetch API
* Async/Await
* Open-Meteo Weather API
* LocalStorage

## 🌐 API Used

This project uses the **Open-Meteo API** to retrieve:

* City location information
* Current temperature
* Humidity
* Wind speed
* Rainfall
* Weather conditions
  
## ⚙️ How It Works

1. Enter a city name in the search box.
2. The application finds the city's location using the Geocoding API.
3. Latitude and longitude are obtained.
4. The Weather API is called using these coordinates.
5. Current weather information is displayed on the dashboard.
6. The searched city is saved in **Recent Searches** using browser LocalStorage.

## 🕘 Recent Searches

The application stores the **last 5 searched cities** in the browser's LocalStorage.

Users can:

* Click a recent city to search again.
* Clear the complete search history using the **Clear History** button.

## ⚠️ Error Handling

The application handles:

* Empty city input
* Invalid city names
* City not found
* Weather API errors
* Network/API connection errors


## 🎯 Learning Outcomes

This project provides hands-on experience with:

* Asynchronous JavaScript programming
* `fetch()` API integration
* `async/await`
* Working with JSON data
* DOM manipulation
* Error handling
* Browser LocalStorage
* Git and GitHub version control

## 🤖 AI-Assisted Development

AI assistance was used during development for:

* API integration guidance
* Debugging and error analysis
* Code improvement
* Feature implementation
* Git commit message generation
* Documentation preparation

## 📝 Sample Git Commit

```bash
git add index.html
git commit -m "feat: implement weather dashboard"
git push
```

## 📄 License

This project is created for educational and learning purposes.
