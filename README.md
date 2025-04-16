# IP_Project

The Reddit Feed Viewer is a modern web application developed using React, Vite, and Tailwind
CSS that enables users to browse and explore content from any subreddit on Reddit. The
application provides a responsive, user-friendly interface that displays posts with their associated
metadata while incorporating modern design principles and smooth interactions.

live link -> https://redditfeedviewer.netlify.app/






Here's a concise and powerful `README.md` for running a **Vite + React Native** project (note: Vite is not natively used with React Native, but with **React web**. However, we can reimagine the setup using tools like **Expo** and **Metro** bundler for React Native and bring Vite-like speed to the DX):

```markdown
# Vite-Powered React Native Project

Reimagining React Native with Vite-speed development. Powered by **Expo**, **Metro**, and optimized with a blazing-fast workflow.

Quick Start

```bash
1. Clone the repo
git clone https://github.com/your-username/vite-react-native
cd vite-react-native

2. Install dependencies
npm install
# or
yarn

3. Start the development server
npx expo start
```

Running on Device

- **Web**: Press `w`
- **Android**: Press `a`
- **iOS**: Press `i` (macOS only)
- **QR Code**: Scan using Expo Go app

Project Structure

```
vite-react-native/
├── App.tsx              # Entry point
├── app/                 # Screens and navigation
├── assets/              # Images, fonts, icons
├── components/          # UI building blocks
├── constants/           # Reusable constants
├── utils/               # Helpers and utilities
└── package.json
```

Tooling

- **Expo** – handles native build & bundling
- **Metro** – JS bundler optimized for React Native
- **TypeScript** – strict typing, modern tooling
- **EAS (optional)** – for production builds

Reimagined Dev Workflow

Fast refresh, modular components, and first-class DX. While Vite doesn't bundle React Native directly, we leverage the **Vite mindset**: speed, simplicity, and modularity.
