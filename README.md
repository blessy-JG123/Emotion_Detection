Emotion-Aware Speech Recognition using Whisper and Audio Features
This project combines speech recognition and emotion detection from audio using OpenAI's Whisper model, librosa for audio processing, and a basic SVM classifier for emotion prediction.

📌 Features
Speech Transcription using OpenAI's Whisper model

Emotion Recognition from audio features (MFCC + Pitch)

MP4 to WAV Conversion using MoviePy

End-to-end Emotion-Aware Speech Recognition Pipeline

🛠️ Dependencies
Install the required packages:

bash
Copy
Edit
pip install openai-whisper librosa numpy scikit-learn moviepy
📂 File Structure
main.py: Core script for transcription and emotion detection

audio.ogg: Example audio input file (replace with your own)

model training: SVM trained on randomly generated dummy features (replace with real labeled dataset for production)

🚀 How to Run
Make sure your environment has all dependencies installed.

Place your audio/video file (MP4 or OGG) in the same directory.

Run the script:

bash
Copy
Edit
python main.py
🧠 Workflow
Convert MP4 to WAV using moviepy.

Transcribe Speech using Whisper.

Extract Features using librosa:

MFCCs (Mel-Frequency Cepstral Coefficients)

Pitch (mean over time)

Train Emotion Classifier (SVM) – dummy data used for demonstration.

Predict Emotion and display transcription, language, and emotion.

🎯 Sample Output
text
Copy
Edit
Transcription: Hello, how are you today?
Language Detected: en
Detected Emotion: happy
📦 Deliverables
Script for transcription and emotion detection

Audio feature extraction functions

Pre-trained SVM classifier (demo only – train with real data for production)

🔬 Future Improvements
Replace dummy data with a real labeled emotion dataset.

Use deep learning (e.g., CNN, LSTM) for emotion classification.

Improve pitch feature extraction and normalization.

Integrate with a web app (Streamlit or Flask) for live demo.

