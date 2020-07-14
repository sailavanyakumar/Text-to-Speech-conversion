# Text-to-Speech-conversion
Text to speech conversion using python language
<ul>
  <li>Uses google's text to speech library</li>
  <li>gTTS library*</li>
  <li>Simple code snippet in python for general text to speech conversion</li>
  </ul>
  
 <hr>
 !code:
 
 <p>
  from gtts import gTTS<br>
import os<br>
text = "Hello user! You are currently explorig the outcome of the library developed by Google India team..To customize our voice to your text enter the text here"<br>
language = 'en'<br>
speech = gTTS(text=text, lang=language,slow=False)<br>
speech.save("test.mp3")<br>
os.system("start test.mp3")<br>
#taking input from user
t_input=input("Enter input for text to speech conversion")<br>
speech1 = gTTS(text=t_input, lang=language,slow=False)<br>
speech1.save("given.mp3")<br>
os.system("start given.mp3")<br>
</p>
