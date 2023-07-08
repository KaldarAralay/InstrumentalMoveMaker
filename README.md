# InstrumentalMoveMaker

Video Creator from Image and Audio
This Python script, movie.py, is designed to create a video from a single image and an audio file. The script uses the PIL (Pillow), pydub, and moviepy libraries to achieve this.

#Functionality
The script is designed to work as follows:

It searches the directory it is located in for subdirectories.
For each subdirectory, it checks for an audio file and an image file.
If both types of files are found in the same directory, the script creates a video from them. The image is displayed for the duration of the audio. The resulting video is saved in the same subdirectory.
How to Use
Place the movie.py file in a directory on your machine.
Create a new subdirectory inside the directory containing movie.py. The name of the subdirectory can be anything you choose.
Inside this new subdirectory, place the audio file (supported formats include .mp3, .wav, etc.) and the image file (supported formats include .jpg, .png, etc.) that you want to convert into a video.
Run the movie.py script from a terminal or command prompt. The script will process the files in the new subdirectory and produce a video file named video.mp4.
#Requirements
This script requires Python 3.x and the following Python libraries:

Pillow: This is a fork of the Python Imaging Library (PIL). It adds some user-friendly features like file saving and loading, image resizing, etc.
pydub: A simple and easy-to-use Python library for audio manipulation. This script uses pydub to check if a file is an audio file.
moviepy: A Python library for video editing. In this script, moviepy is used to create a video clip from an image and an audio file.
Please ensure you have installed all the necessary Python libraries listed in the requirements.txt file before running the script. To install the requirements, you can use pip:

shell
Copy code
pip install -r requirements.txt
#Troubleshooting
If you encounter an error related to a missing library, please ensure that you have installed all the libraries listed in the requirements.txt file. If the error persists, please open an issue on this GitHub repository with details about the error message and the steps you took before encountering the error.

Let me know if you need any further details or modifications.
