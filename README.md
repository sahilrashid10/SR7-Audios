```
# 🎵 SR7 AUDIOS - Your Favorite Music Player

Welcome to **SR7 AUDIOS**, a lightweight and dynamic audio player application built with **HTML**, **CSS**, and **JavaScript**. This project combines a clean UI with responsive functionality, offering a smooth experience for playing and managing music.

## 🚀 Features

- **Interactive Song List**: Displays a list of songs with corresponding play buttons.
- **Play/Pause Control**: Easily toggle music playback.
- **Dynamic Song Banner**: Shows the current song being played with its details.
- **Progress Bar**: Visualize and control audio progress.
- **Next/Previous Buttons**: Navigate seamlessly through the playlist.
- **Responsive Design**: Adapted to work on various screen sizes.

## 💂️ Project Structure

```
.
├── index.html        # Main HTML file
├── style.css         # Styling for the UI
├── script.js         # JavaScript functionality
├── songs/            # Audio files
├── covers/           # Song cover images
├── assets/           # Additional assets (e.g., logo, gif)
```

## 🎨 Design and UI

- **Fonts**: 
  - `Ubuntu` for a modern and clean navigation bar.
  - `Varela Round` for a sleek, rounded font style in the song list and player.
- **Dark Theme**: A combination of black and purple for an elegant aesthetic.
- **Animated Elements**: Includes smooth transitions and a "Now Playing" gif for a lively experience.

## 🔅 How to Use

1. Clone this repository to your local system:
   ```bash
   git clone https://github.com/your-username/sr7-audios.git
   ```
2. Navigate to the project directory:
   ```bash
   cd sr7-audios
   ```
3. Open the `index.html` file in your browser:
   ```bash
   open index.html
   ```

## 📷 Screenshots

### 🎵 Homepage  
![Homepage Screenshot](assets/screenshot-homepage.png)

### 🎶 Playing Song  
![Playing Screenshot](assets/screenshot-playing.png)

## 🎶 Adding Your Songs

1. Add your `.mp3` files to the `songs/` directory.
2. Add cover images to the `covers/` directory.
3. Update the `songs` array in `script.js`:
   ```javascript
   let songs = [
       { songName: "New Song Name", filePath: "songs/your-song.mp3", coverPath: "covers/your-cover.jpg" }
   ];
   ```

## 🔧 Built With

- **HTML5**: Semantic structure for web content.
- **CSS3**: Styling with animations and responsive design.
- **JavaScript**: Logic for playback, progress bar, and interactions.

## 🌟 Future Enhancements
- Allow users to create custom playlists.
- Add more pages other than home page.

---

🎶 **Enjoy your music with SR7 AUDIOS!**
```

