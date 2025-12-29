# Happy Birthday Sameera! 🎂

An interactive 3D birthday card experience built with modern web technologies. This project features a seamless transition from a 2D intro to a fully 3D interactive scene using Three.js.

## ✨ Features

- **Interactive Intro**: A clean, dark-mode 2D introduction with a "blow out the candles" interaction using a custom GIF.
- **3D World Experience**: Upon interaction, the scene transitions to a rich 3D environment rendered with **Three.js**.
- **Immersive Atmosphere**:
  - **Video Background**: Features a looping anime-style sunset city skyline (Attribution: Vecteezy).
  - **3D Assets**: High-quality 3D models including a detailed cake and a wooden table.
  - **Lighting**: Custom ambient, directional, and point lighting to create a warm, magical mood.
- **Interactive Note**: A glowing 3D note on the table that reveals a personalized message when clicked.
- **Responsive Design**: Auto-adjusts the 3D camera and renderer for different screen sizes.

## 🛠️ Technologies Used

- **HTML5 & CSS3**: For the structure, styling, and 2D animations.
- **JavaScript (ES6)**: Logic for state management and interactions.
- **Three.js**: The core library for rendering the 3D scene.
  - `GLTFLoader`: For importing `.glb` 3D models.
  - `OrbitControls`: For managing camera interaction (customized to lock zoom/pan).

## 🚀 How to Run

1. **Clone/Download** the repository or folder.
2. Ensure you have the following asset files in the directory:
   - `birthday.html` (Main application file)
   - `cake.glb` (3D Model)
   - `animes1.mp4` (Background Video)
   - `Birthday Cake Pink Sticker.gif` (Intro Image)
3. **Open** `birthday.html` in any modern web browser (Chrome, Firefox, Safari, Edge).
   - *Note*: For the best experience, use a local server (e.g., VS Code "Live Server" extension) to ensure 3D assets load correctly without CORS issues, though Firefox often allows local loading directly.

## 📂 Project Structure

```
├── birthday.html           # Main entry point containing HTML, CSS, and JS
├── cake.glb                # 3D Cake model
├── animes1.mp4             # Background video file
├── Birthday Cake Pink Sticker.gif # Intro animation asset
├── CC.md                   # Creative Commons / Attribution info
└── README.md               # Project documentation
```

## 📜 Credits & Attribution

- **Background Video**: [Anime Stock Videos by Vecteezy](https://www.vecteezy.com/free-videos/anime)
- **Fonts**: 'Patrick Hand' and 'VT323' from [Google Fonts](https://fonts.google.com/).
- **3D Models**: Sourced generic assets for educational/personal use.

---
