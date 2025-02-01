# 🎵 Command-Line Music Player  

This is a simple command-line music player written in C for Windows. The program allows you to play, stop, skip songs, and manage a playlist of `.wav` audio files.  

## 🚀 Prerequisites  
- Windows Operating System  
- C Compiler (e.g., MinGW or Microsoft Visual Studio)  
- Sound Card or Audio Output Device  

## 🔧 Getting Started  

1. Compile the C code using a C compiler. For MinGW, use:  
   ```sh
   gcc music_player.c -lwinmm -o music_player
2. Run the executable:
   ```sh
   music_player.exe

🎶 Usage
The program will display a menu with options for:

- Playing songs
- Stopping playback
- Skipping songs
- Managing the playlist
Follow the on-screen instructions to interact with the music player.

📌 Notes
The program scans the current directory for .wav files and initializes the playlist during startup.
Ensure that your music files are in the .wav format.
