Project - JARVIS (YOUR PERSONAL VIRTUAL ASSISTANT)

JARVIS  is a Python-based virtual assistant that responds to your voice commands. It can perform various tasks like opening websites, playing music, fetching news, and answering your questions using OpenAI's powerful GPT-3.5-turbo model.

 Features: 

*  Voice Recognition:  Listens and understands your spoken commands using the `speech_recognition` library. JARVIS activates upon hearing the wake word "Jarvis."
*  Text-to-Speech:  Converts text to speech for natural interaction, using either the `pyttsx3` library for local conversion or `gTTS` (Google Text-to-Speech) with `pygame` for playback.
*  Web Browsing:  Opens websites like Google, Facebook, YouTube, and LinkedIn based on your voice commands.
*  Music Playback:  Connects with a user-defined `musicLibrary` module to play songs through web links.
*  News Fetching:  Retrieves and reads the latest news headlines using the NewsAPI.
*  OpenAI Integration:  Handles complex queries and generates responses using OpenAI's GPT-3.5-turbo model, acting as a general virtual assistant similar to Alexa or Google Assistant.

 Workflow: 

1.  Initialization:  JARVIS greets you with "Initializing Jarvis...."
2.  Wake Word Detection:  Listens for the activation command "Jarvis."
3.  Acknowledgement:  Confirms activation by saying "Ya."
4.  Command Processing:  Analyzes your voice command to determine the action (e.g., open website, play music, fetch news, etc.).
5.  Speech Output:  Uses the `speak` function to respond using either `pyttsx3` or `gTTS`.

 Libraries Used: 

* `speech_recognition`
* `webbrowser`
* `pyttsx3` (or `gTTS` and `pygame`)
* `musicLibrary` (user-defined module)
* `requests`
* `openai`
* `os`

 Getting Started: 

1.  Install Required Libraries:  Use `pip` to install the necessary libraries:

   ```bash
   pip install speech_recognition webbrowser pyttsx3 requests openai gTTS pygame
   ```

2.  Create `musicLibrary.py`:  Create a custom `musicLibrary.py` file to define a song dictionary with song names as keys and their corresponding web links as values.

3.  Set API Keys:  Replace `<Your Key Here>` with your actual API keys for NewsAPI and OpenAI.

4.  Run the Script:  Execute the main Python script using `python main.py` (or your script's name). 

 Enjoy using JARVIS! 


https://github.com/harshgupta372/Project.Jarvis/assets/167362291/cb95ea96-c618-4227-9ef9-22799710ba12

