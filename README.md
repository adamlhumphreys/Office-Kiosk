# Office-Kiosk
 Basically a JavaScript based Chromecast look-alike

## How To Use
Copy all the images you want to cycle through into the 'i' folder.
Open the index.htm file in a browser, (only tested in Chrome so far).
Drag-and-drop those images in the 'i' folder into the browser where you've opened index.htm, and you'll be prompted to save list.js.
Save list.js in the Office-Kiosk folder, overwriting the existing one if there's already one there.
Optionally insert your OpenWeather API credentials and location from openweathermap.org in the first line of the getWeather() function, otherwise remove calls to the function and the weather related tags in the HTML body.
Refresh the page and enjoy. Cast it to your Chromecast and see if someone notices. :)
