# Apple Core-dination

*Shared World Voice-Controlled Game*

Language, Action, & Perception Software Project

Winter 2020-2021

## How to Use (Playing the Game)
1. Clone repository or download zip file.
2. Have Python 3 installed, or download it [here](https://www.python.org/).
3. To install dependencies, do *one* of the following two options: 
	1. Run `pip install -r requirements.txt` to install dependencies.
		- *You may need to install PyAudio manually. Refer to [SpeechRecognition site](https://pypi.org/project/SpeechRecognition/#pyaudio-for-microphone-users) to install according to your operating system.*
		- *You may need to install SpeechBrain directly from GitHub: https://github.com/speechbrain/speechbrain#quick-installation*

	2. Alternatively, install the `applecore.yml` file:
		* Download [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/download.html). 
		* Run `conda env create -f applecore.yml`.
		* Run `conda activate applecore`.
		* Install SpeechBrain from: https://github.com/speechbrain/speechbrain#quick-installation

4. Navigate to `gamefiles/` on local machine.
5. Run `python3 game.py` or `python game.py` to play the game.

## Accessories Required for Playing
Apple Core-dination requires an **internet connection** to make use of Google Speech Recognition, a **keyboard**, and a working **microphone** on your device.

## Demo
For a brief game demonstration, visit https://www.youtube.com/watch?v=0x6ZBAsmyY0.
<p align="center">
	<img src="gamefiles/img/applecore-demo-thumbnail.png" alt="Demo Thumbnail Image" />
</p>
