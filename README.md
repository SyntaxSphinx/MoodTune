# MoodTune 🎵

**MoodTune** is a premium, interactive web application that curates and streams Spotify playlists tailored dynamically to your current mood and preferred language. Built with a modern, glassmorphic dark-mode interface, it offers a seamless and responsive audio experience directly inside the browser.

---

## ✨ Key Features

- **Explore Moods Navigation Flow**: A dedicated `/moods` selection page housing interactive mood tiles (Happy, Sad, Calm, Energetic, Romantic, Chill).
- **Vibrant Glassmorphic Design**: Clean aesthetic utilizing CSS frosted-glass (`backdrop-filter`) blur effects, Harmony HSL gradients, and glow transition animations.
- **Dynamic Background Theming**: The application background dynamically updates its radial gradient glow depending on the selected mood (e.g., warm sunset orange for Happy, deep ocean blue for Sad, fresh emerald mint for Chill).
- **Inline Spotify Player Embed**: Integrated official Spotify Embed player widget in a floating bottom-bar, allowing tracks to be played directly on your website instead of redirecting users to Spotify.
- **Smart "Play Random Song"**: Let the app surprise you! Instantly picks a random song matching your selected mood and language filter, playing it inside the inline player.
- **Responsive Layout**: Designed mobile-first using Bootstrap 5 grid utility classes.

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML5, Vanilla CSS3 (Custom styling system + glassmorphism), Vanilla JavaScript (ES6)
- **Database/Storage**: JSON-based static database (`songs-1.json`) containing tracks tagged by language, artist, and mood.
- **Third-Party Integrations**: Spotify Play Button Embed player

---

## 🚀 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/your-username/moodtune.git
cd moodtune
```

### 2. Install dependencies
Make sure you have Python installed. Install the required packages:
```bash
pip install -r requirements.txt
```

### 3. Run the development server
```bash
python app.py
```

### 4. Open the App
Navigate to `http://127.0.0.1:5000` in your web browser.
