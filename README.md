# WaveTube Player

WaveTube is a lightweight and responsive YouTube player built with **HTML, CSS, and JavaScript**.

It allows users to paste a YouTube link and watch the video through the **YouTube IFrame Player API**.

---

## ✨ Features

- Responsive design for desktop and mobile devices
- Light and dark theme support
- Automatic theme preference saving
- YouTube IFrame Player API integration
- Supports multiple YouTube URL formats
- Video playback status updates
- Clear player functionality
- Mobile-friendly interface
- No backend or build tools required

---

## 🔗 Supported YouTube Links

WaveTube supports the following YouTube URL formats:

### Standard YouTube Video

```text
https://www.youtube.com/watch?v=VIDEO_ID
```

### Short YouTube Link

```text
https://youtu.be/VIDEO_ID
```

### YouTube Shorts

```text
https://www.youtube.com/shorts/VIDEO_ID
```

### Embedded YouTube Video

```text
https://www.youtube.com/embed/VIDEO_ID
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sec-coder-69/wavetube.git
cd wavetube
```

### 2. Run the Project

WaveTube does not require Node.js, npm, a backend, or any build tools.

You can open the `index.html` file directly in your browser.

Alternatively, you can start a local development server.

#### Using Python

```bash
python -m http.server 8000
```

Then open the following address in your browser:

```text
http://localhost:8000
```

---

## 🎮 How to Use

1. Open the WaveTube application.
2. Paste a valid YouTube URL into the input field.
3. Click the **Play** button.
4. Use the controls inside the video player.
5. Click the **Theme** button to switch between light and dark mode.
6. Click **Clear** to remove the current video.

---

## 📂 Project Structure

```text
wavetube/
├── index.html
└── README.md
```

The project is contained in a single HTML file.

The `index.html` file includes:

- HTML page structure
- CSS styling
- Responsive design
- JavaScript functionality
- YouTube IFrame Player API integration
- Theme management
- YouTube URL processing

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**
- **YouTube IFrame Player API**
- **Browser `localStorage`**

---

## 🌐 How It Works

WaveTube uses the **YouTube IFrame Player API** to load and control YouTube videos directly inside the web application.

The application:

1. Accepts a YouTube URL from the user.
2. Detects the supported YouTube URL format.
3. Extracts the YouTube video ID.
4. Loads the video using the YouTube IFrame Player API.
5. Updates the playback status based on player events.
6. Allows the user to clear the current video.
7. Stores the selected theme preference using browser `localStorage`.

---

## 🎨 Theme Support

WaveTube supports both **Light Mode** and **Dark Mode**.

The selected theme can be stored using browser `localStorage`, allowing the application to remember the user's preference between sessions.

---

## 🎨 Customization

The application colors can be customized by editing the CSS variables inside `index.html`.

Example:

```css
:root {
  --blue: #1976d2;
  --dark-blue: #125ca3;
  --background: #eef1f5;
  --page: #f8f9fb;
  --card: #ffffff;
}
```

You can also customize:

- Application title
- Text
- Colors
- Layout
- Spacing
- Buttons
- Player container
- Responsive breakpoints
- Light and dark theme styles

All major customization can be performed directly inside `index.html`.

---

## 📱 Responsive Design

WaveTube is designed to work across different screen sizes, including:

- Desktop computers
- Laptops
- Tablets
- Mobile phones

The interface automatically adjusts its layout according to the available screen size.

---

## ⚠️ Important Notes

- An internet connection is required to load the YouTube IFrame Player API.
- YouTube videos must allow embedded playback.
- Some videos may not be available for embedding due to YouTube restrictions.
- Playback availability may depend on YouTube policies, browser settings, and device capabilities.
- Screen-off playback may not work on every browser or mobile device.
- WaveTube does not host or download YouTube videos.
- Video content is streamed through YouTube's embedded player.

---

## 🔒 Privacy

WaveTube does not require a backend or user account.

The application runs primarily in the user's browser.

Theme preferences may be stored locally using browser `localStorage`.

YouTube playback is handled through the YouTube IFrame Player API and is subject to YouTube's own policies and privacy practices.

---

## 📦 Requirements

WaveTube requires only:

- A modern web browser
- Internet connection for YouTube playback
- JavaScript enabled in the browser

No additional software or dependencies are required.

---

## 💻 Browser Compatibility

WaveTube is designed to work with modern browsers that support standard HTML5, CSS3, and JavaScript features.

Recommended browsers include:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari
- Other modern Chromium-based browsers

---

## 🧩 Project Architecture

WaveTube follows a simple client-side architecture:

```text
User
  │
  ▼
YouTube URL Input
  │
  ▼
URL Validation & Video ID Extraction
  │
  ▼
YouTube IFrame Player API
  │
  ▼
Embedded YouTube Player
  │
  ▼
Video Playback
```

There is no separate backend server or database.

---

## 🚫 No Backend Required

WaveTube is a fully client-side application.

There is:

- No backend
- No database
- No API server
- No authentication system
- No Node.js requirement
- No npm dependencies
- No build process

The application can run directly from the `index.html` file or through a simple local HTTP server.

---

## 📁 Repository

GitHub Repository:

```text
https://github.com/sec-coder-69/wavetube
```

---

## 📜 License

This project is open source and available under the **MIT License**.

To use the MIT License, create a file named:

```text
LICENSE
```

in the root directory of the repository and add the standard MIT License text.

---

## 👨‍💻 Author

**WaveTube**

GitHub:

```text
https://github.com/sec-coder-69/wavetube
```

---

## ⭐ Contributing

Contributions, suggestions, and improvements are welcome.

If you would like to contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test the application.
5. Commit your changes.
6. Push the branch.
7. Open a Pull Request.

---

## 📝 Future Improvements

Potential future improvements include:

- Playlist support
- Video history
- Improved player controls
- Keyboard shortcuts
- Picture-in-picture support
- Better mobile controls
- Additional theme customization
- Video metadata display
- Improved URL validation
- Accessibility improvements

---

## 🎯 Project Goal

The goal of WaveTube is to provide a **simple, lightweight, responsive, and easy-to-use YouTube playback interface** without requiring a backend, database, or complex development environment.

---

**WaveTube — Simple. Lightweight. Responsive.**
