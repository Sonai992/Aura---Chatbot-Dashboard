# Aura - Chatbot Dashboard

Aura is a polished, responsive chatbot dashboard prototype built as a single-page HTML application. It combines a glassmorphic interface, animated widgets, chat interactions, file attachments, voice input controls, account menus, and conversation management.

## Features

- Animated welcome screen with suggested prompt chips
- Responsive chat thread and message composer
- Text and Enter-key message sending
- Image and file attachment selection
- Microphone and live audio visualization UI
- Weather widget with cycling weather effects
- Sports score and breaking-news widgets
- Projects, history, settings, sign-in, and sign-out drawers
- Pin and delete controls for conversation history
- Light and dark appearance modes
- Mobile-specific layouts and reduced-motion support

## Project Structure

```text
Aura – Chatbot Dashboard/
├── Aura – Chatbot Dashboard.html
└── @Readmi.md
```

## Getting Started

This project has no build process or external package dependencies. To run it:

1. Open `Aura – Chatbot Dashboard.html` directly in a modern browser.
2. Alternatively, serve the folder with a local static server:

```powershell
python -m http.server 8000
```

3. Visit `http://localhost:8000/Aura%20%E2%80%93%20Chatbot%20Dashboard.html`.

## Usage

- Select a prompt chip or type a message in the composer.
- Use the plus button to attach an image or file.
- Use the microphone button to enable browser voice-input visualization.
- Open the top-right account menu for projects, history, settings, or sign-in.
- Pin or delete entries from the History drawer.
- Open Settings to switch between light and dark appearance.

## Demo Behavior

This repository is a front-end prototype:

- Chat replies are simulated with a placeholder response.
- Sign-in accepts demo credentials and does not connect to an authentication service.
- Market data, sports scores, weather, and news are displayed as sample interface data.
- File attachments are shown in the composer and message but are not uploaded.
- Microphone access requires browser permission and a secure context such as `localhost` or HTTPS.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Canvas API
- Web Audio API
- Web Speech/media browser APIs
- Google Fonts: Manrope

## Browser Support

Use a current version of Chrome, Edge, Firefox, or Safari for the full experience. Voice and canvas features may vary by browser and operating system.
