# GenAI Image to Voice Description

Convert images into descriptive stories with voice narration using Generative AI models.

## Overview

This project utilizes Generative AI models to convert images into descriptive stories with voice narration. It employs state-of-the-art natural language processing and computer vision techniques to generate compelling narratives based on uploaded images. The generated stories are then summarized and narrated in audio format, providing users with an immersive storytelling experience.

## Features

- **Image-to-Text Conversion**: Utilizes the blip model to extract text from uploaded images.
- **Story Generation**: Generates short stories from the extracted text using GPT (Generative Pre-trained Transformer) models.
- **Text-to-Speech Conversion**: Converts generated stories into audio format using the ESPnet text-to-speech model from HuggingFace.
- **Summarization**: Summarizes the generated stories for brevity and clarity.
- **Streamlit Web App**: Provides a user-friendly interface for uploading images and listening to generated stories.

## Usage

1. Upload an image.
2. Wait for the model to process the image and generate a story.
3. Listen to the generated story in audio format.
4. Optionally, view the summarized version of the story.

## Requirements

- Python 3.6+
- Streamlit
- Transformers
- LangChain
- HuggingFace API
- ESPnet

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/<YOUR_USERNAME>/GenAI-Image-to-Voice-Description.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## How to Run

Run the following command:

```bash
streamlit run app.py
