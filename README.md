# TEXT-TO-SPEECH
YT

""" how to make python speak something or how to make
 text to speech"""
# install pyttsx3
import pyttsx3
engine = pyttsx3.init()
speak_input = input("Say Something : ")
engine.say(speak_input)
engine.runAndWait()
