<h1>Weather App</h1>
<p>This is a simple weather application that fetches weather data from the <a href="https://openweathermap.org/api" target="_blank">OpenWeather API</a>.</p>

<h2>Features</h2>
<ul>
  <li>Displays current weather for a given city.</li>
  <li>Fetches data from OpenWeather API in real-time.</li>
  <li>Shows temperature, weather description, humidity, and wind speed.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li>HTML, CSS, JavaScript</li>
  <li>OpenWeather API</li>
</ul>

<h2>How to Run the App</h2>
<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/adarshupadhyay21/WebWeatherApp.git</code></pre>
  </li>
  <li>Open <code>index.html</code> in your browser.</li>
  <li>Enter a city name to get the current weather information.</li>
</ol>

<h2>Setup and Configuration</h2>
<p>To use this app, you need an API key from OpenWeather. Follow these steps:</p>
<ol>
  <li>Sign up at <a href="https://openweathermap.org" target="_blank">OpenWeather</a> and get your API key.</li>
  <li>Add your API key to the JavaScript file:
    <pre><code>const apiKey = 'ENTER_Your_API_KEY';</code></pre>
  </li>
</ol>

<h2>Example API Call</h2>
<pre><code>https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY</code></pre>

<h2>License</h2>
<p>This project is licensed under the MIT License.</p>
