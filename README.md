<h2>Rain 🌧️ alert App</h2>

Sources hourly weather data for 12 hours from the Open Weather API and uses Twilio to alert if it will rain in day. 
Schedule it to run at a particular time in the day, and it will check whether it will rain and send a message.

<h2>Steps to install:</h2>
<ol>
  <li>Go to openweather and get a free tier API KEY.</li>
  <li>Configure it to send a request along wih the latitude and longitude to the one call API, exclude minute, and daily data/</li>
  <li>Sign up for a free tier Twilio account/</li>
  <li>Depending on the weather condion codes set up whether to send a message or not.</li>
  <li>Deploy it on a platform (pythonanywhere works well!) and schedule it to run once in the morning. It will let you know if you need to take an umbrella ☔ with you.</li>
</ol>
