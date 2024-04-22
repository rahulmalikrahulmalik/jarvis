# jarvis
ipomrt pyttsx3     engine = pyttsx3.init(`sapi5`) Voice = engine.getproperty(`Voices`) print(voices) engine.setproperty(`voices`, voices[0].id)   def speak(audio): engine.say(audio) engine.runAndwait()  if __name__ == '__main__': speak('RAHUL is A good boy')
