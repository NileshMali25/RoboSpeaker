# RoboSpeaker
This is my first project
import os
print("Welcome to RoboSpeaker 1.1 Created by niluu")
import pyttsx3
while True:
    x=input("Enter What you want me to speak:")
    if x=="q":
        print("Thanks for using Robospeaker.")
        break
    engine = pyttsx3.init()
    engine.say(x)
    engine.runAndWait()


