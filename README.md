Voice-Enabled IMDb Movie Search
This Python project allows users to search for movies using voice commands. It combines speech recognition, text-to-speech synthesis, and the IMDb database to provide details about movies such as the title, release year, IMDb rating, and a brief plot summary.

Features
Voice recognition for capturing the movie name

Text-to-speech interaction with the user

Real-time search using IMDb's movie database

Provides movie title, release year, IMDb rating, and plot outline

Differentiates between past and upcoming movie releases

Technologies Used
imdbpy – Accesses IMDb movie data

pyttsx3 – Converts text to speech

SpeechRecognition – Converts speech to text

pyaudio – Captures microphone input

datetime – Handles date comparison
Example Interaction
Program: "Say the movie name"

User: "Inception"

Program:

"Searching for Inception"

"I found these:"

"Inception - 2010"

"Inception was released in 2010, has an IMDb rating of 8.8. The plot summary of the movie is: A thief who steals corporate secrets..."

Notes
Ensure your microphone is properly connected and functional.

You may need to allow microphone access depending on your operating system or IDE.

Run the script in a quiet environment for better voice recognition accuracy.
