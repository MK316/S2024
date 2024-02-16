## 📙 Text-to-Speech (TTS) 

+ Text-to-Speech (TTS) technology converts written text into spoken words. It's like having a robot that can read out loud whatever text you give it. This technology is used in various applications, from helping visually impaired individuals to read texts to providing voice responses in virtual assistants like Siri or Google Assistant.

+ Let's take an example from gTTS (Google Text-to-Speech), a popular Python library that uses Google's Text-to-Speech API to convert text into audio. gTTS is straightforward to use and can generate speech in multiple languages.

+ Example with gTTS:
Imagine you want to convert the sentence "Hello, world!" into spoken words using gTTS in Python. Here's a simple way to do it:

1. First, you need to install the gTTS library. You can do this by running the command:

```
pip install gTTS

```

2. Then, you write a small Python script to use gTTS:

```
from gtts import gTTS
import os

# The text you want to convert to audio
my_text = "Hello, world!"

# Language we want to use
language = 'en'

# Passing the text and language to the engine,
# here we mark slow=False to tell the module that
# we want the converted audio to have a high speed
my_obj = gTTS(text=my_text, lang=language, slow=False)

# Saving the converted audio in a mp3 file named
# 'welcome.mp3'
my_obj.save("hello_world.mp3")

# Playing the converted file
os.system("mpg321 hello_world.mp3")

```

3. In this example, gTTS takes the string "Hello, world!" and converts it into an audio file in English ('en'). The slow=False parameter tells gTTS that you want the speech to be at a normal speed. After generating the audio, it's saved to a file named hello_world.mp3, which you can play with any media player that supports MP3 files.
