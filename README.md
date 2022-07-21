# Meeting Summarizer App 
[Website](https://meeting-summarizer.netlify.app)
## Web App built using ReactJS for summarizing meetings
### PS-1 Project for Jio Platforms

## Project Description
- User can upload the audio file of meeting on homepage to get the transcription on `/convert` route
- Audio file is stored in Firebase cloud
- Used AssemblyAI for transcription

### Steps to generate the summary:

1. Open the website mentioned above, upload the audio.
2. Generate the speech-to-text file.
3. Open the Extractive/Abstractive summarisation notebooks on Google Colab.
4. Copy and paste the text generated from the website into the text field in google colab.
5. Run the file.
6. The summary is printed at the end.
