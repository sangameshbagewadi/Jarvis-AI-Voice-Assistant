# Jarvis-Voice-Assistant

Jarvis is actually an ai which was introduced in the first Iron Man movie. A very spohisticated AI for Tony Stark made programmers think about making their on AI Assistants. This JARVIS also got it's inspiration fro Iron Man movies.

JARVIS - JOEL'S ARTIFICIAL REALISTIC VIRTUAL INTERNET SERVICE"

There had been many different versions of my Jarvis in the past few months. First, it had been a text assistnat, then speech came and this version is my first every fully artificially intelligent jarvis program with AIML. This is completely written in Python and it is compatible with almost all systems (Mac OS, Linux and Windows(Recommended)). Being written in Windows, it is more suitable to be used in Windows. Some minor changes will be needed to run on other os.

Specialty of JARVIS
Fully autonomous with AIML and Lisp as the brain of JARVIS.
Support with offline speech recognition with the help of vosk models.
Offline Text to Speech service with pyttsx3.
More surer program launching mechanism.
Very powerful chat mode with ALICE files.

Setup Procedures
For getting JARVIS up and running, the instructions are given below :

Environment setup
You need to have Python 3.7 or later versions top run Jarvis. Jarvis is initially developed in Python 3.8.9, so getting the same version will be nice to avoid any other issues but 3.7 or later is also okay
Please note : Make sure to download Python 64 bit only ! Some modules are compatible only with 64 bit version. Also add Python to your system PATH.

Installing the required modules
First, navigate to this cloned repository and open cmd and then type :
pip install -r requirements.txt
Most of the times, you may run into an error saying 'no module named pyaudio'. If there is any error on installing SpeechRecognition, do check out this website. Please download the ".whl" file of pyaudio of your python version. Link to website - https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio . After downloading that, pip install that .whl file. For Eg:
pip install PyAudio‑0.2.11‑cp38‑cp38‑win_amd64.whl
The above wheel is suitable for Python 3.8 version. amd64 means 64 bit and win32 means 32-bit. First pip install the wheel and then again run pip install -r requirements.txt . After all these procedures, we are ready to start testing out JARVIS.
