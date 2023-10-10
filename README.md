# Making Chrom Extention Momentum App with JavaScript (Nomad Coder) 
 </div>
<h2>Purpose/Goal</h2>
<ul>
 <li>Review and apply CSS styles</li>
 <li>Utilize local storage to create a login page and to-do list</li>
 <li>Implement basic JavaScript functions in the browser</li>
 <li>Incorporate external API</li>
</ul>
<div>
<p> ☞ Pusblished Chrom app website: https://quiet-strudel-77b924.netlify.app/ </p>
<h2>Using Skills</h2>
<div>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=CSS&logoColor=black"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS&logoColor=black"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=CSS&logoColor=black"/>
<h2>Main Features</h2>
<ul>
 <li>Login using local storage</li>
 <li>Real-time clock</li>
 <li>Random background images and quotes</li>
 <li>To-do list using local storage</li>
 <li>Weather and location (geolocation)</li>
</ul>
</div>
<h2>JavaScript Descriptions</h2>
<h3>Background.js & Quotes.js</h3>
- Establishing an array encompassing diverse backgrounds and quotes, followed by the application of the Math.random and Math.floor functions to precisely select and present a randomly chosen background alongside an associated quote</br>
<h3>Clock.js</h3>
- Utilize the Date object to retrieve the current time. Employ setInterval() and setTimeout() to establish timers, enabling the execution of tasks at fixed intervals or after a specified time, respectively <br/>
<h3>Greeting.js</h3>
- When a user submits an event, store user information in the local storage. Depending on the presence of stored user information, hide the existing form and display a greeting message thereafter. <br/>
<h3>Todo.js</h3>
- Convert the user-submitted value into a stringified object and store it in the local storage as an array containing 'id' and 'todo'
- Represent the information in the local storage by utilizing the presence or absence of stored data using 'li' elements
- Implement functionality for adding and deleting 'li' elements
<h3>Weather.js</h3>
- Utilize the OpenWeatherMap API to display real-time weather and temperature information based on the current location </br>
<div>
<h2>References</h2>
 <ul>
  <li>Lecture: https://nomadcoders.co/javascript-for-beginners</li>
  <li>API:https://api.openweathermap.org/data/2.5/weather?lat=${lat}&lon=${lon}&appid=${API_KEY}&units=metric</li>
 </ul>
</div>



 
  




