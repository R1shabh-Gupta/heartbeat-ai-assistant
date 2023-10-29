# Heartbeat AI

This is a simple project designed to create a basic Python-based virtual assistant. 

## Project Overview

As someone passionate about programming and technology, I've always been intrigued by the idea of having a personal AI assistant. This project allows us to explore that concept and learn how to create a basic virtual assistant using Python. With my virtual assistant, I can perform a variety of tasks simply by giving voice commands. Some of the key functionalities include:

- Searching for information on Wikipedia.
- Opening websites like Google and YouTube.
- Launching my preferred code editor or IDE with a voice command.

## Getting Started

1. **IDE Choice**: You can use any IDE you prefer, but in this tutorial, Visual Studio Code is used. Feel free to use your preferred IDE or text editor.

2. **File Setup**: Create a new Python file named `main.py`.

## Dependencies
Before diving into the project, I need to make sure that I have the necessary dependencies installed. Use requirements.txt file do install dependences.
```bash
pip3 install -r requirements.txt
```

## Building My Assistant

The core of my virtual assistant is the `speak()` function. It's responsible for making my assistant talk by converting text to speech. The `pyttsx3` library is used for this purpose.

The `wishme()` function greets me based on the current time, giving me a personalized experience. I'm using the `datetime` module to achieve this.

To understand my voice commands, I've created the `takeCommand()` function, which captures my input via the microphone and processes it as a string. This function is made possible by the `speechRecognition` library.

## Key Functionalities

My virtual assistant can perform various tasks based on my voice commands. Some of these include:

- **Searching on Wikipedia**: If I mention "wikipedia" in my query, my assistant fetches a summary from Wikipedia and reads it aloud.

- **Opening YouTube Site**: It can open the YouTube website in a web browser when I say "open YouTube."

- **Opening Google Site**: Similar to YouTube, it opens the Google website when I say "open Google."

- **Knowing the Current Time**: I can ask my assistant for the current time, and it will provide me with the time.

## Personal Reflection

While my virtual assistant may not be a full-fledged AI, it's a great starting point. As someone passionate about the potential of AI, this project allows me to explore the fundamentals and gradually build more advanced capabilities.

## Conclusion

This project has laid the foundation for my very first virtual assistant. I'm excited to explore further and enhance its capabilities. Feel free to reach out if you have any questions or suggestions. Enjoy building your own virtual assistant!
