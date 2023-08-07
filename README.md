# Vue.js Weather App

## Live Link / Demo Link: 🔗
[Deployed app](https://incredible-moonbeam-340408.netlify.app/)

## Table of Contents
* [About the Project](#about-the-project)
* [Screenshots](#screenshots)
* [Technologies Used](#technologies-used)
* [Setup / Installation](#setup--installation)
* [Approach](#approach)

## About the Project: 📚
Welcome to the Vue Weather App! This project is a simple and intuitive weather application built using Vue.js, designed to provide real-time weather information for any location around the world.

## Screenshots: 📷
![Weather App](https://github.com/alibinauanov/vue-weather/blob/main/weather.gif)

## Technologies Used: ☕️ 🐍 ⚛️
* Vue.js
* JavaScript
* Yarn
* Open Weather Map API

## Setup / Installation: 💻
#### Download VueJS</br>
```npm -g i  @vue/cli``` or ```yarn global add @vue/cli```</br>
Choose ```default (babel, eslint)```

#### Project setup</br>
```vue create vue-weather```. vue-weather is name of folder, so you can change the name of folder

#### API
Open this [link]([url](https://home.openweathermap.org/api_keys)) and create your own API KEY. Then copy your key.</br>
App.vue -> line 34 -> you can paste your own key that you got before.

#### Run Project</br>
```yarn serve```

## Approach: 🚶
#### Design Patterns and Architecture
The Vue Weather App follows a component-based architecture, a core principle of Vue.js development. It's organized into multiple Vue components that each have a specific responsibility, enhancing code readability, maintainability, and reusability.

Key Components:
* App.vue: The main application component that serves as the entry point for the app. It manages the main layout, user input, and data display.
* SearchBox.vue: Handles user input and triggers weather data fetching upon pressing the Enter key.
* WeatherDisplay.vue: Displays the fetched weather data, including location, date, temperature, and weather condition.

#### Code Styles and Practices
The project adheres to best practices and coding standards to ensure clean and maintainable code.

Key Code Styles:
* Component Structure: Each Vue component is organized into sections, including template, script, and style, ensuring a clear separation of concerns.
* CSS Styling: Styles are scoped to the respective components using CSS modules, preventing global style conflicts.
* Data Management: The app effectively uses Vue's reactivity system to update the UI based on data changes.
* API Interaction: The OpenWeatherMap API is integrated to fetch weather data based on user input.
* Error Handling: Proper error handling is implemented, such as displaying a help message when no weather data is available.

#### Features and Functionality
The Vue Weather App offers the following features:
* Weather Data: Fetches and displays real-time weather information, including temperature and weather conditions.
* Search Functionality: Enables users to search for weather data by entering the name of a city.
* Responsive Design: The app is designed to be responsive, adapting to various screen sizes and devices.
* User-Friendly UI: Clear and intuitive user interface with helpful messages for better user experience.
