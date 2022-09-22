# File_Encryptor

## Create script to encrypt files and folder

### Usage

python encrypt.py path(file or folder)

Examples:
    python encrypt.py test.txt(file)
    or
    python encrypt.py ./testdir(folder)

encrypted files("original_file_name.bin") will be generated in original location after the program running

Example :
    
    Original file : Binary.txt(file)
    Encrypted file : Binary.bin
    
    Original Folder : ./Cipher
    Encrypted Folder : ./Cipher.bin

# Speech-to-Text Converter

This Python script converts the Speech input into Text using NLP (Natural Langauge Processing).

## Requirements

**Installation Required** :

* Python Speech Recognition module:

    `pip install speechrecognition`

* PyAudio:
  * Use the following command for linux users

    `sudo apt-get install python3-pyaudio`

  * Windows users can install pyaudio by executing the following command in a terminal

    `pip install pyaudio`

* Python pyttsx3 module:

    `pip install pyttsx3`

### How to run the script

-   Enter the audio input by speaking into the microphone.
-   Run converter_terminal.py script
-   Output Text will be displayed

# Convert_JPEG_to_PNG

This project contains a simply python script to change file extension from .jpeg to .png

## Requirements
Pillow module

`pip install pillow`

## Two methods:

I accomplished this task in two ways
### Using Terminal
- Add the image in jpeg format with name as 'input' in this folder.
- Run converter_terminal.py script
- output image will be generated in this folder

### Using GUI
Just run the converter_GUI.py script and pick any jpeg image from any location and then press 'Convert Jpeg to Png'
