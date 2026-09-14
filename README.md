# YT-PLAYER
WaveTube is a lightweight, responsive YouTube player built with HTML, CSS, and JavaScript. It supports YouTube link parsing, embedded playback through the IFrame API, light and dark themes, status updates, clear controls, and mobile-friendly layouts optimized for smaller screens.
WaveTube Player
WaveTube is a lightweight, responsive YouTube player built with HTML, CSS, and JavaScript. Paste a YouTube video link, load it instantly, and watch it through the YouTube IFrame Player API.

Features
Responsive layout for desktop and mobile screens
YouTube URL support for:
Standard watch links
Shortened youtu.be links
YouTube Shorts
Embedded YouTube links
YouTube IFrame API integration
Light and dark themes
Theme preference saved with localStorage
Video playback status updates
Clear button for resetting the player
Mobile-friendly interface
No backend or build tools required
Supported YouTube URLs
WaveTube supports links such as:

text


https://www.youtube.com/watch?v=VIDEO_ID
https://youtu.be/VIDEO_ID
https://www.youtube.com/shorts/VIDEO_ID
https://www.youtube.com/embed/VIDEO_ID
Getting Started
1. Clone the repository
bash


git clone https://github.com/your-username/wavetube.git
2. Open the project folder
bash


cd wavetube
3. Run the application
Open index.html directly in a modern web browser.

For better compatibility, you can also use a local development server:

bash


python -m http.server 8000
Then visit:

text


http://localhost:8000
How to Use
Paste a valid YouTube URL into the input field.
Select Play.
Use the controls inside the embedded video player.
Select the moon or sun button to change the theme.
Select Clear to reset the player.
Project Structure
text


wavetube/
├── index.html
└── README.md
The project is currently contained in a single index.html file, including the page structure, styling, and JavaScript functionality.

Technologies Used
HTML5
CSS3
JavaScript
YouTube IFrame Player API
Browser localStorage
Notes
The YouTube IFrame API requires an internet connection.
Some videos may not be available for embedding.
Playback behavior may vary depending on YouTube restrictions, browser settings, and device capabilities.
Screen-off playback is not guaranteed on every device or browser.
Customization
You can customize the application by editing the CSS variables near the beginning of the file:

css


:root {
  --blue: #1976d2;
  --dark-blue: #125ca3;
  --background: #eef1f5;
  --page: #f8f9fb;
  --card: #ffffff;
}
You can also change the application name, text, colors, spacing, and responsive layout directly in index.html.

License
This project is available under the MIT License. Add a LICENSE file to the repository if you want to distribute it officially under that license.
