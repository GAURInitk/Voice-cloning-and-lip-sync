# Voice-cloning-and-lip-sync
Mentors
M Uzzwal
Rahul Bhimkari
Mentees
Aadharsh Ramachandran
Gauri Aggarwal
Parihasa K Reddy
Utkarsh Shukla
📌 Aim
The project aims to develop a system that generates realistic speech through voice cloning and synchronizes lip movements with minimal input data. This enables seamless dubbing, virtual avatars, and content creation.

📖 Introduction and Overview
Voice cloning and lip synchronization play a crucial role in AI-driven content creation, dubbing, and virtual avatars.

This project leverages:

Tortoise TTS for zero-shot voice cloning, requiring only 5-10 seconds of speaker audio to generate realistic speech.
Wav2Lip to synchronize the generated voice with lip movements in videos, ensuring natural and high-quality speech animation.
🛠️ Technologies Used
Voice Cloning
🔹 Tortoise TTS – Zero-shot voice cloning

Lip Syncing
🔹 Wav2Lip – Modifies lip movements to match generated speech

Frameworks & Libraries
🔹 PyTorch
🔹 Gradio 🔹 FFmpeg

Backend
🔹 Flask – Serving the application

Evaluation Metrics
🔹 MOS (Mean Opinion Score) – Measures speech quality
🔹 SyncNet Scores – Evaluates lip-sync accuracy

📂 Datasets
Short audio clips (5-10 sec) of different speakers for training/testing.
Video samples to evaluate lip-sync accuracy with cloned speech.
Open-source datasets for TTS and lip-syncing models (e.g., LRS2, VoxCeleb).
🏗️ Model and Architecture
1️⃣ Tortoise TTS
Generates high-quality, expressive speech from limited data.
2️⃣ Wav2Lip
Modifies lip movements to synchronize with the cloned voice.
3️⃣ Modular Deep Learning Pipeline
✔ Input audio processing
✔ TTS-based speech generation
✔ Lip-syncing using Wav2Lip
✔ Video output generation

🎨 Gradio Interface
📝 Input: Enter text for speech synthesis.
🎙️ Choose Speaker: Select your preferred voice.
📺 Preview: View the final synchronized video.

🎯 Conclusion
This project successfully integrates zero-shot voice cloning with lip synchronization, producing natural and expressive speech-driven animations.

✨ It enhances:
✅ AI-based dubbing
✅ Virtual avatars
✅ Personalized content creation

🚀 Offering an innovative approach to multimedia generation!
