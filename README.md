# TFC 88 - Audio Controller

A modern web-based audio controller built with Astro and Tone.js that allows users to manipulate and process audio files in real-time. This project provides a sleek, PlayStation and Akai MPC inspired interface for audio manipulation with various effects and controls.

## Features

- **Audio Upload & Playback**
  - Drag and drop or click to upload audio files
  - Support for multiple audio formats (MP3, WAV, M4A, AAC, OGG, WEBM)
  - Pre-loaded sample tracks
  - Basic playback controls (Play, Pause, Stop, Loop)

- **Real-time Audio Processing**
  - Playback rate control with pitch adjustment
  - BPM detection and display
  - Multiple audio effects:
    - Reverb with adjustable decay time
    - Delay with configurable time and feedback
    - Distortion with intensity control
    - Pitch shifting with semitone adjustment

- **Mobile-Friendly Design**
  - Responsive layout that works on both desktop and mobile devices
  - Touch-optimized controls
  - PlayStation-inspired UI with custom fonts and styling

## Technical Details

### Built With
- [Astro](https://astro.build/) - Web framework
- [Tone.js](https://tonejs.github.io/) - Web Audio framework
- [web-audio-beat-detector](https://github.com/audiojs/web-audio-beat-detector) - BPM detection
- Custom CSS with PlayStation-inspired design

### Audio Processing
The application uses Tone.js for audio processing, providing:
- Real-time audio manipulation
- High-quality audio effects
- Low-latency playback
- Mobile-optimized audio context

### UI Components
- Nostalgic interface inspired by Playstation, Akai MPC and similar beat machines.
- Custom fonts (Armygedon, Esportiva, Share Tech Mono)
- Responsive design with mobile optimizations
- Interactive sliders and buttons
- Visual feedback for active effects

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```
4. Open your browser to localhost

## Usage

1. **Loading Audio**
   - Click the upload area or drag and drop an audio file
   - Use the "TRACKS" button to access pre-loaded samples

2. **Playback Controls**
   - Use Play/Pause/Stop buttons for basic control
   - Toggle Loop button for continuous playback
   - Adjust playback rate using the slider

3. **Effects**
   - Toggle effects using their respective buttons
   - Adjust effect parameters using the sliders that appear
   - Combine multiple effects for complex sound manipulation

## Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Mobile Support
- iOS Safari
- Android Chrome
- Other modern mobile browsers

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request. 