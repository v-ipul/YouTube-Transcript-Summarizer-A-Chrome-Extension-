# YouTube Transcript Summarizer A Chrome Extension 
#It will make a request to a backend REST API where it will perform
#Natural Language Processing and respond with a summarized
#version of a YouTube transcript. Also Summarize transcripts from a
#non-English video and display it in English language


#  High-Level Approach
Get transcripts/subtitles for a given YouTube video Id using a Python API.
Perform text summarization on obtained transcripts using HuggingFace transformers.
Build a Flask backend REST API to expose the summarization service to the client.
Develop a chrome extension which will utilize the backend API to display summarized text to the user.
#  Applications
Meetings and video-conferencing - A system that could turn voice to text and generate summaries from your team meetings.
Patent research - A summarizer to extract the most salient claims across patents.
