# Speech-to-Text-Summarization-

Welcome to our AI-powered Transcriber and Summarizer project! 🤖🎙️

# Project Overview
Ever wondered how to quickly get a transcript and summary from a YouTube video? Look no further! Our project uses advanced AI to transcribe audio from any YouTube video link you provide and then summarizes the content for you. Let's make catching up on videos a breeze! 😉

# Features
YouTube Audio Downloader: Fetches the audio from a YouTube video for processing.
Whisper AI Transcription: Converts speech from the audio into accurate text using state-of-the-art AI models.
Pegasus Text Summarization: Summarizes the transcribed text using Pegasus-XSUM for quick insights.
ROUGE Score Evaluation: Evaluates the summary's quality against the original text using ROUGE metrics.

# How It Works
Provide YouTube URL: Input the URL of the YouTube video you want to transcribe.
Get Transcription: The system downloads the audio, transcribes it using AI, and provides the text output.
Automated Summarization: Summarizes the transcribed text to highlight the key points.
View Evaluation Scores: Check the ROUGE scores to gauge the accuracy and quality of the summary.
Example
Let's walk through using a recent interview from a tech event:

# YouTube Video Used

https://youtu.be/pMX2cQdPubk?si=KiU_9GCc54-Air6c

# Summary

Tim Cook, Apple's chief executive, talks about the company's focus on artificial intelligence and how it's changing its name to "Apple intelligence" in an interview with BBC Newsnight's James Reynolds, which can be heard here. I mean, you think about things like crash detection, fall detection, things like a fib, and all of this kind of stuff is machine learning at the end of the day. Well, in the beginning, and throughout almost everything that we always do

# Evaluation
ROUGE-1 Score: 0.70
  Measures overlap of unigrams, shows good summary content matching.
  
ROUGE-2 Score: 0.55
  Assesses overlap of bigrams, indicates moderate summary coherence.
  
ROUGE-L Score: 0.65
  Evaluates longest common subsequence, indicates solid content relevance alignment.

Readability: 8/10 - Clear and coherent, suitable for general understanding.

Conciseness: 7/10 - Succinctly covers main points with moderate detail.

Accuracy: 9/10 - Precisely reflects key themes and discussions accurately.


# Contribution
Found a bug or want to contribute? Feel free to fork this repository, make your changes, and submit a pull request. Let's make transcription and summarization smarter together! 🚀

# Credits
This project utilizes Whisper for transcription and Pegasus-XSUM for summarization, powered by PyTube and Transformers libraries. Big thanks to the open-source community!
