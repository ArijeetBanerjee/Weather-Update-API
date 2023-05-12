# Weather-Update-API
• Developed a node js (express and HTTPS) backend-based web application to get live weather updates by entering the location/city details from the front end. To get the weather details I have used a web scrapping technique on a popular open-source external weather API.
![Build-Weather-App-in-JavaScript](https://github.com/ArijeetBanerjee/Weather-Update-API/assets/76873956/d1b24be1-0bdc-4d44-9e2d-911aade3f343)
To create this project (Weather App in JavaScript). First, I  created three Files: HTML, CSS & JavaScript File. 

Obtain an API key from the OpenWeatherMap API website by creating an account and following the instructions provided.

Create a new HTML file and add the necessary HTML tags, such as the <head> and <body> tags.

Within the <head> tags, link your CSS file using the <link> tag and your JavaScript file using the <script> tag.

Create the necessary HTML elements to display the weather information, such as a div to hold the temperature, another div to hold the weather description, and an image tag to display an icon representing the weather.

In the JavaScript file, define a function to fetch the weather data from the OpenWeatherMap API using the fetch() method and passing in the API key and the location data, such as the city name or zip code.

Parse the JSON response from the API using the json() method and extract the necessary data, such as the temperature, weather description, and icon URL.

Update the HTML elements created earlier with the retrieved weather data using the innerHTML property.

Add an event listener to a form or button element to trigger the weather update function when the user inputs their desired location and submits the form.

Finally, add some CSS to style your HTML elements and make your weather update web app visually appealing.
