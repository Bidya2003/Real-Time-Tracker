Realtime Location Tracker
With the help of JavaScript, Firebase Realtime Database, and HTML Geolocation API, this application allows users to track their current location in real-time and displays it on a map. It provides a seamless user experience and helps individuals keep track of their location without any hassle.

Features
Show realtime locations
Show latest locations (7) in database
Browser-based
Marker info
Usage
Go to locationtracker.vercel.app in any device.
Enter a nickname, and then click on the "Add my location to the map".
Track only those who have been online on the map in the last 10 seconds.
Don't forget! to grant location permissions and enable location sharing.

Screenshots
homepage

Database Structure
{
  "locations": {
    "emrecoban": {
      "label": "emrecoban",
      "latitude": 41.2477,
      "longitude": 36.2395,
      "timestamp": 1680825786101,
    },
    "emre's phone": {
      "label": "emre's phone",
      "latitude": 25.2467,
      "longitude": 63.4395,
      "timestamp": 1680825786101,
    }
  }
}
Built with
JavaScript
Firebase Realtime Database
HTML Geolocation API
Google Maps API
Support
Sponsor to me on GitHub.
Give a star to this repo.
Follow me on Twitter @emreshepherd, or GitHub @emrecoban.
Buy me a coffee, or book: https://www.buymeacoffee.com/emrecoban
References
HTML Geolocation API
Google Maps JavaScript API
Firebase Realtime Database
License
This project is available as open source under the terms of the MIT License.
