# Vision Sync

> **Vision Sync** uses real-time computer vision to recognize objects and human facial expressions, translating live visual streams into procedural musical soundscapes powered by TensorFlow.js, MediaPipe, Tone.js.

---

## Key Features

- **Live Object Detection**: Utilizes TensorFlow.js and COCO-SSD for instant bounding-box object classification in the browser.
- **Facial Landmark & Emotion Recognition**: Powered by Google MediaPipe Vision tasks for real-time face tracking and subtle affective cues.
- **Dynamic Procedural Audio Synthesis**: Generates responsive micro-melodies, bass lines, and harmonic soundscapes on the fly using Tone.js and Web Audio API.
- **AI Scene & Vibe Interpretation**: Leverages the Gemini API for intelligent multimodal scene analysis and dynamic music vibes.
- **Modern Interactive UI**: High-contrast, responsive dashboard built with React 19, Tailwind CSS v4, Motion, and Lucide icons.

---
### Live Demo
[https://vision-sync-alex.vercel.app](https://vision-sync-alex.vercel.app)

## Tech Stack

- **Frontend**: [React 19](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Machine Learning & Vision**: 
  - [@tensorflow/tfjs](https://www.tensorflow.org/js) & [@tensorflow-models/coco-ssd](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd)
  - [@mediapipe/tasks-vision](https://developers.google.com/mediapipe/solutions/vision)
- **Audio & Music Synthesis**: [Tone.js](https://tonejs.github.io/) & Web Audio API
- **AI & Multimodal**: [@google/genai](https://github.com/google-gemini/gemini-js) (Gemini API)
- **Animations & Icons**: [Motion](https://motion.dev/), [Lucide React](https://lucide.dev/)

---

### Prerequisites

- [Node.js](https://nodejs.org/) (version 18 or higher recommended)
- [npm](https://www.npmjs.com/) (or yarn / pnpm / bun)
- A webcam connected to your computer

## Available Scripts

- `npm run dev` — Starts the local Vite development server on port `3000`
- `npm run build` — Compiles TypeScript and creates an optimized production bundle in `dist/`
- `npm run preview` — Locally previews the production build
- `npm run lint` — Runs TypeScript type-checking without emitting files

---

## Security & Privacy

- **No Secrets in Public Repositories**: The `.gitignore` file is strictly pre-configured to ignore all `.env` files. **Never commit your actual API keys to GitHub.**
- **Camera Privacy**: All computer vision inference (TensorFlow.js & MediaPipe) runs **100% locally in your browser** on the client side.

---
# ⭐ Support

If you like VISION_SYNC, don't forget to leave a ⭐ on GitHub.

It helps the project grow.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

<div align="center">

## Made with ❤️ by ΛLΞX JΛMΞS
