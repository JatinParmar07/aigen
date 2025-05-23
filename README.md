# AI Story Generator

This repository contains a web-based story generation app using the GPT-2 language model. It allows users to input a custom story beginning, choose a genre, and receive multiple AI-generated continuations. The application is built using Streamlit and Hugging Face Transformers.

## Features

- Selectable story genres (Fantasy, Horror, Sci-Fi, Romance, etc.)
- Generates three unique story continuations per input
- Expandable views for each story
- Downloadable output as a plain text file

## Usage

To use this repository:

1. Ensure your environment meets the version requirements listed below.
2. Install all dependencies.
3. Run the Streamlit application.

### Requirements

- Python version: `>=3.8, <=3.11`
- Required Python packages:
  - `streamlit>=1.22.0`
  - `transformers>=4.26.0`
  - `torch>=1.13.0, <2.2.0`
- requirements.txt is necessary for deployed app on Streamlit.

## Streamlit
- Make sure the python version is 3.10 or less when you run Streamlit app.
- Streamlit App link: https://ai-gen.streamlit.app/#ai-story-generator
