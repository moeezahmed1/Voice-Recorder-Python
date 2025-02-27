# Voice-Recorder-Python
A simple and user-friendly voice recorder application built using Python and Tkinter.

Python Voice Recorder
A simple and lightweight voice recorder application built using Python. This project allows users to record audio for a specified duration and save it as a .wav file. It features a graphical user interface (GUI) created with Tkinter and uses the sounddevice and scipy libraries for audio recording.

Features
User-Friendly Interface: Easy-to-use GUI for recording audio.

Customizable Recording Duration: Specify the recording time in seconds.

Real-Time Countdown: Displays a countdown timer during recording.

Save Recordings: Saves recordings as .wav files in the current directory.

Cross-Platform: Works on Windows, macOS, and Linux.

Requirements
To run this project, you need the following Python libraries:

tkinter (included in Python standard library)

sounddevice

scipy

wavio

numpy (required by sounddevice and scipy)

You can install the required libraries using pip:

bash
Copy
pip install sounddevice scipy wavio numpy

How to Use
Clone the Repository:

bash
Copy
git clone https://github.com/your-username/python-voice-recorder.git
cd python-voice-recorder
Run the Application:

bash
Copy
python voice_recorder.py
Enter Recording Duration:

Enter the desired recording duration in seconds in the input box.

Start Recording:

Click the "Record" button to start recording. A countdown timer will appear.

Save Recording:

Once the recording is complete, the audio will be saved as recording.wav in the current directory.

Code Structure
voice_recorder.py: The main script containing the GUI and recording logic.

voicerecorder.png: Icon and logo image for the application.

Customization
Change Output File Name: Modify the write("recording.wav", freq, recording) line in the Record() function to save the file with a different name.

Change Audio Quality: Adjust the freq (sample rate) and channels parameters in the sound.rec() function.

Troubleshooting
Error: "Couldn't open voicerecorder.png":

Ensure the voicerecorder.png file is in the same directory as the script.

Use an absolute path if the file is located elsewhere.

Error: "ModuleNotFoundError":

Ensure all required libraries are installed using pip.

No Sound Recording:

Check your microphone settings and ensure it is properly connected.

Contributing
Contributions are welcome! If you find any issues or want to add new features, feel free to open an issue or submit a pull request.

Author
Moeez Ahmed
GitHub: moeezahmed1
Email: moeezzafarlahore@gmail.com
