# Screen Recorder

This is a lightweight and intuitive screen recording web application. It allows users to record their screen or camera, capture screenshots, apply live color filters, and track recording duration with a timer.

## Features

- Live video preview from camera
- Start and stop screen recording
- Capture screenshots from live video
- Apply visual filters (orange, brown, pink, transparent)
- Visual timer for recording duration
- Animations for recording and screenshot feedback
- Auto-download of recorded video and images
- Fully responsive layout with intuitive controls

## Technologies Used

- HTML5 and CSS3
- Vanilla JavaScript (ES6)
- MediaRecorder API
- Canvas API
- CSS Animations

## How It Works

1. Camera access is requested using `navigator.mediaDevices.getUserMedia()`
2. Media stream is recorded using the `MediaRecorder` API
3. Screenshots are captured using the `<canvas>` element and `drawImage()`
4. Filters are applied using overlay divs and `background-color`
5. Timer is updated every second using `setInterval()`
6. Recorded files and snapshots are saved using a programmatically triggered anchor (`<a>` with `download`)

## Folder Structure

