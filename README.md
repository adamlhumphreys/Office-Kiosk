# Office-Kiosk
 Basically a JavaScript based Chromecast look-alike

## How To Use
- Copy all the images you want to cycle through into the 'i' folder. Note the validFileExtensions variable in case I missed one.
- Open the index.htm file in a modern browser.
- Drag-and-drop those images in the 'i' folder into the browser where you've opened index.htm, and you'll be prompted to save list.js.
- Save list.js in the Office-Kiosk folder, overwriting the existing one if there's already one there so it can be ready next time you need to reopen index.htm.
- Optionally insert your OpenWeather API credentials and location from openweathermap.org in the first line of the getWeather() function. Don't have an account? It's easy to set up a free account: https://home.openweathermap.org/users/sign_up Otherwise, remove calls to the function and the weather related tags in the HTML body.
- Enjoy! Cast it to your Chromecast and see if someone notices. :)
