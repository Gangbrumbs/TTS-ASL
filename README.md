# TTS-ASL

Project #1 TTS/ST(ASL)

Audio Recognition

Technologies/Languages:
API that is suited for audio I/O (
Java/Python
Standardized Formats 
	- Input
		- Android
			- MP3
			- WAV
		- IOS
			- AAC
			- ALAC
		- Windows
			- PCM
	- Output
		- MP3

  
Delegations:
Heng:
Java Audio Recognition Techniques
With/o API's

Elijah:
Python Audio Recognition Techniques
With/o API's

Workflow 1st Iteration:

Rules:
Speech file must be in spoken English
Translated text will be in English
1st Iteration speech file limit is 1 minute

User input speech file -> 
Speech file is standardized from original format to MP3 ->
Speech is translated to text ->
Text is printed -> TBD

Developer Notes:
Heng#1:
Used Sphinx4(API) from CMU Sphinx to implement speech recognition in the java project.
Used JAVE(library) to implement file format conversion from the above mentioned formats to MP3

Heng#2:
Can't find any good free apis in java, switched to python with whisper API, but this api does everything in 4 lines of code and its very powerful.
decided to extend this to something more, talked to lance about it and want to add a GUI to it
decided to use python GUI since we have 0 knowledge about how to connect java-python files
this GUI will have 2 functions , 1 is to drag a audio file to it and it will transcribe it (size can't be more than 25MB), another function is to press a button to record a temporary audio file like Whatsapp does and it will transcribe as the first function does (under 60 seconds)
for the transcribed text, 2 ways can be done: download a txt file with the text in users computer or make a area in the GUI to display the text (this part is yet to be discussed)
still learning about GUIs, have some understandings for tkinter in python, also looking for a new GUI if possible

