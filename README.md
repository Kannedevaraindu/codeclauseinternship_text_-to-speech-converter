# codeclauseinternship_text_-to-speech-converter
import pyttsx3

def data():
    print("code clause internship basic project")
    
    print("this project name is text-to-speech-converter")
    input_data = input("enter the data you want to convert from text to speech-")
    a = pyttsx3.init()
    a.say(input_data)
    a.runAndWait()

data()
