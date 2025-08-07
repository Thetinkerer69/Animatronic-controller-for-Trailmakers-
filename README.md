Trailmakers Animatronic Music Controller
📝 Project Overview
This is a Python-based application designed for the game Trailmakers. It allows you to create and replay intricate keyboard choreographies for your animatronic builds. The controller synchronizes your key presses with a music track, enabling you to build complex dancing or moving animatronics and play them back perfectly every time.

The application is bundled into a single, user-friendly executable (.exe) file, so your friends can use it on Windows without needing to install Python or any libraries.

✨ Key Features
Keyboard Choreography: Record and save key press sequences with precise timing relative to a music track.

Synchronized Playback: Replay recorded choreographies with perfect synchronization to the music.

Adjustable Latency: Fine-tune the timing of key presses with a global latency offset to match your specific setup.

Simple UI: A clean and easy-to-use graphical interface built with Tkinter.

Portable Executable: The application is packaged as a single .exe file, making it easy to share and run on any Windows PC.

📥 Installation
There are two ways to get the application:

Method 1: Download the Installer (Recommended for Users)
Go to the Releases section of this repository.

Download the latest setup.exe file.

Run the installer and follow the on-screen instructions. This will install the application and all included songs to your system.

Method 2: Run from Source (for Developers)
If you want to modify the code or contribute, follow these steps:

Clone this repository:

Bash

git clone https://github.com/your-username/your-repo.git
Navigate into the project directory:

Bash

cd your-repo
Install the required Python libraries:

Bash

pip install pygame pynput pyinstaller
Run the application:

Bash

python gui_controller.py
🚀 How to Use
Launch Trailmakers and load your animatronic build.

Start the Animatronic Music Controller application.

Select Song: Use the "Select Song" dropdown to choose a music track.

Record Choreography:

Click the "Record Choreography" button.

The recording will begin after a 5-second countdown. During this time, click on the Trailmakers window to make it active.

Press and hold the keys you want to record. The application will log the key-down and key-up events.

To stop, press the Esc key on your keyboard or wait for the song to finish. The choreography will be saved as a .json file.

Play Choreography:

Select the song and the desired .json choreography file.

Click the "Play Choreography" button.

The playback will begin after a 5-second countdown. Click on the Trailmakers window to ensure the key presses are sent to the game.

Stop: Click the Stop button or press the Esc key at any time to halt the process.

🎶 Adding More Songs
The executable includes a songs folder that you can add your own music to.

Open the installation directory (e.g., C:\Program Files\Trailmakers Animatronic Controller).

Inside, you'll find a songs folder.

For each new song, create a new subdirectory with the song's title (e.g., songs/My New Song).

Place the MP3 file inside that subdirectory, making sure its name matches the folder name (e.g., songs/My New Song/My New Song.mp3).

Restart the application to see the new song in the dropdown menu.

⚠️ Important Notes
Game Focus: The controller sends keyboard events to the currently active window. You must click on the Trailmakers game window after the countdown starts to ensure your choreography is executed in-game.

Latency Offset: The "Global Latency Offset (ms)" field allows you to adjust the timing. A positive value delays key presses, while a negative value makes them happen earlier, helping you achieve perfect sync.

🙏 Credits
Developed by: Thetinkerer69

Special thanks to: Gemini, a large language model from Google, for assistance with coding and troubleshooting.
