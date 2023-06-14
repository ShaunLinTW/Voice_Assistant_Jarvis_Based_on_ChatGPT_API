# Voice_Assistant_Jarvis_Based_on_ChatGPT_API
A Voice Assistant - Jarvis, using Python and based on ChatGPT API to response question.

![Jarvis](https://upload.wikimedia.org/wikipedia/en/e/e0/J.A.R.V.I.S._%28MCU%29.png)

## Getting Started
In order to start this project, you need to run the following code in your command to install the package:
```
pip install openai
```
```
pip install pyttsx3
```
```
pip install speech_recognition
```
Above code will install the `openai`, `pyttsx3` and `speech_recognition` packages and all of its dependencies.

If the `speech_recognition` package didn't install successfully, alternatively you can install the package directly from the source code by cloning the Git repository and running the setup.py script:
```
git clone https://github.com/Uberi/speech_recognition.git
cd speech_recognition
python setup.py install
```

## How to Modify the code:
Before you run the program, you can modify a few line of code.

### 1. Add your ChatGPT API to the code:
Add your ChatGPT API key here `"YOUR_API_KEY"`
```
openai.api_key = "YOUR_API_KEY"
```

### 2. Optional code:
You can choose the voice to male or female by change following setting:
```
engine.setProperty('voice', voice[0].id)
```
If you use `voice[0].id`, that will be male voice, but if you want to change to female voice you can replace it to `voice[1].id`.

If you want your voice speed faster, you can change following setting:
```
engine.setProperty('rate', 150)
```
If you want voice speed faster, you need to set the number bigger, if you want the voice speed slower, you can set the number smaller.

Also, if you want to change `Jarvis` name to any other name you want, you can modify the following code:
```
speak("Hello, I am Jarvis. How can I help you today?")
```

## How to run the Jarvis:
Run `python Jarvis.py`
```
python Jarvis.py
```

## How to stop the Jarvis:
Say `thank you for your help` to stop the program, if you want to change to other sentence to stop the program, you can modify the following code:
```
if prompt == "thank you for your help":
      # Exit the program
      sys.exit()
```

## Authors
 **Shaun Lin**
 
## License
This project is licensed under OpenAI.

<img src="https://static-00.iconduck.com/assets.00/openai-icon-2021x2048-4rpe5x7n.png" width="200" height="200" />
