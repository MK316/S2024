## 📙 Text-to-Speech (TTS) 

+ Text-to-Speech (TTS) technology converts written text into spoken words. It's like having a robot that can read out loud whatever text you give it. This technology is used in various applications, from helping visually impaired individuals to read texts to providing voice responses in virtual assistants like Siri or Google Assistant.

+ Let's take an example from gTTS (Google Text-to-Speech), a popular Python library that uses Google's Text-to-Speech API to convert text into audio. gTTS is straightforward to use and can generate speech in multiple languages.

+ Example with gTTS:
Imagine you want to convert the sentence "Hello, world!" into spoken words using gTTS in Python. Here's a simple way to do it:

1. First, you need to install the gTTS library. You can do this by running the command:

```
!pip install gtts
```

2. Then, you write a small Python script to use gTTS:

```
from gtts import gTTS
from IPython.display import Audio, display

# The text you want to convert to audio
text = "Welcome to Python!"

# Creating a gTTS object
tts = gTTS(text=text, lang="en")

# Save the object as mp3 file
tts.save("output.mp3")

# Use IPython's Audio class to play the sound
Audio("output.mp3")
```

3. In this example, gTTS takes the string "Hello, world!" and converts it into an audio file in English ('en'). The slow=False parameter tells gTTS that you want the speech to be at a normal speed. After generating the audio, it's saved to a file named hello_world.mp3, which you can play with any media player that supports MP3 files.

4. Language options [link to gTTS documentation](https://gtts.readthedocs.io/en/latest/module.html#localized-accents)
