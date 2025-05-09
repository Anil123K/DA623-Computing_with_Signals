🎧 CLAP-Based Audio-Text Retrieval

This project demonstrates a zero-shot text-to-audio retrieval system using the CLAP (Contrastive Language–Audio Pretraining) model. 
Given a natural language query like "crow cawing" or "bird chirping", the system returns the most semantically similar audio clip from a local folder — all without any training.

📌 Features

🔍 Text-to-audio search using natural language descriptions

🔊 Index and search a local folder of .wav or .mp3 files

📈 Cosine similarity-based matching using CLAP embeddings

🖼️ Bar chart visualization of similarity scores

🌐 t-SNE plot to visualize embedding proximity 

🧠 Background

CLAP is a multimodal model trained to align audio and text into a shared semantic space. Similar to CLIP (image-text), CLAP enables audio understanding using text prompts. This project builds an interactive retrieval system using these capabilities, implemented entirely in Google Colab.

🚀 Getting Started

Clone the repository or open the Colab notebook.

Place your audio files (.wav/.mp3) in a folder like /content/audio_clips/.

Run the notebook to:

Embed all audio clips

Enter a text prompt

Retrieve and play the most relevant audio

📚 References

CLAP: Contrastive Language-Audio Pretraining – [https://arxiv.org/abs/2211.06687](https://arxiv.org/pdf/2206.04769)

Video Presentation

Drive Link- https://drive.google.com/file/d/1xlz5UeVcNNuyBWxu2V2WbHRvvMQOOEbA/view?usp=drive_link

YouTube Link- https://youtu.be/YdwD-eDoQYs

