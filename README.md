Sound-Controlled Flappy Bird Game
A simple sound-controlled Flappy Bird-style game made using Python, OpenCV, and PyAudio. In this game, the player controls the bird's jumps using sound input, such as clapping or speaking.

Features
Control the bird using sound intensity detected via your microphone.
Obstacles (pipes) that scroll across the screen, with gaps that the bird must pass through.
Real-time score display.
Game Over screen when the bird hits an obstacle or the ground.
Requirements
To run this game, ensure you have the following installed:

Python 3.x
OpenCV (opencv-python)
NumPy
PyAudio
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/vidhan66/sound-controlled-flappy-bird
cd sound-controlled-flappy-bird
Install required libraries:
bash
Copy code
pip install opencv-python numpy pyaudio
Ensure that the bird image (bird.webp) is in the same directory as the script or adjust the file path accordingly.
How to Play
Run the game script:
bash
Copy code
python sound_bird_game.py
Use sound (like clapping or speaking loudly) to make the bird jump.
Avoid hitting the pipes and stay within the screen boundaries.
Game Mechanics
The bird jumps when the sound intensity surpasses a certain threshold.
Gravity pulls the bird down when no sound input is detected.
Each time the bird successfully passes a pipe, you gain a point.
If the bird hits a pipe or the screen edges, it's game over.
Controls
Sound: Use sound intensity to control the bird's jumps.
Quit: Press q to exit the game at any time.
Notes
Adjust the intensity threshold in the code if the game isn't responding to your sound input as expected.
Future Improvements
Adding background music and sound effects.
Enhancing the graphics and adding animations.
Implementing difficulty levels based on the score.
License
This project is open-source and available under the MIT License.
