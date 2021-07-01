# Project Infrasound
## An MOOC / E-Learning model app that helps facilitate assistive learning for people with Hearing Disability

## Motivation
- Over 5% of the world’s population(430 million people) require rehabilitation to address their ‘disabling’ hearing loss (432 million adults and 34 million children). 
- More often than not, they have imperfect development of speech and language skills.
- Students with this disability often have difficulty in maintaining their academic performance and gaining knowledge in today’s fast paced world.
- It is estimated that by 2050 over 700 million people – or one in every ten people – will have disabling hearing loss.

An efficient software to aid in such student's learning is truly the need of the hour. 

## Features

## Softwares and Libraries Used:
 - Python 
 - Flask  
 - SQLAlchemy 
 - HTML5 
 - CSS3 
 - Javascript
 - Bootstrap
 - Pyaudio

# Steps to Run it locally:

## Prerequisites
Make sure you have Python 3.7 or higher installed on your system to run the application. 
Also install venv library to install the dependencies in a virtual environment using the command:
pip install venv

## Steps:

1. First download the zipped folder Code.zip and then unzip it. 
2. Open a Command Prompt/Terminal and navigate to the folder where you have unzipped it and enter that directory.
3. Create a virtual environment using the following commands:
   `virtualenv  t4sne`
4. Then to activate the environment type:
   For windows:
   `t4sne\Scrips\activate`

   For Mac/Linux:
   `source t4sne/bin/activate`
   Now type the following to install all the dependencies:
   `pip install -r requirements.txt` 
   Wait for it to install everything.
5. Next type:
   `pipwin install pyaudio`
6. Now finally run:
   `python application.py`

Finally, open any browser and type in localhost:5000 or 127.0.0.1:500

# Future Enhancements:

## Lip Reading and Sign Language
In the lip reading part the tutorial only focuses on single words, but it can be extended to a sentence to provide advanced exercises and the same can be implemented for sign language. 

## Speech Assistance
There can be added functionality where a text to speech engine first converts the text entered to speech and then a human face that enunciates clearly how to speak that sentence. This will help users imitate the same sounds and thus improve their pronunciation capabilities.

## Transcript
The major problem with the transcript feature was the inefficiency of the speech-to-text engine as it’s a multi-step process of first extracting the audio from the video and then parsing the audio to generate text. This currently makes the text lag 6-7 seconds behind the video but it can be improved significantly!

