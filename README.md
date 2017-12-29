# react-redux-weather-app
React-Redux weather app that uses OpenWeather API to return current and forecasted weather for a given location. This App is built based on Stephen Grider's Udemy course.

This App utilizes:
- [React](https://reactjs.org/)
    - [redux-promise](https://www.npmjs.com/package/redux-promise) for middleware
    - [axios](https://www.npmjs.com/package/axios) for promise based http requests
    - [react-sparklines](https://github.com/borisyankov/react-sparklines) for beautiful and expressive sparklines
- [Redux](https://redux.js.org/)
- [OpenWeatherMap API](http://openweathermap.org/forecast5) for 5-day forecast
- [Webpack](https://webpack.github.io/) for bundling
- [Babel](https://babeljs.io/)

![REACT-REDUX-WEATHER-APP](https://media.giphy.com/media/3o751RDO3azkk6MyU8/giphy.gif)

## Running app locally

1. Install all dependencies with below command
```
npm install
```
2. Sign-up for [OpenWeatherMap Account](https://home.openweathermap.org/users/sign_up) and get the free API key. Replace the variable ```API_KEY``` value with this key in the file ```index.js``` inside actions folder.
3. Get [Google Maps API key](https://developers.google.com/maps/documentation/javascript/get-api-key) and replace it in below script line available in the file ```index.html```
```
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY"></script>
```
4. Open command prompt and run ```npm start```

