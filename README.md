# OCR with Google Gemini API

This repository contains a simple web application that uses the Google Gemini API to perform Optical Character Recognition (OCR) on uploaded images. The app accepts image uploads or pasted screenshots, sends them for processing through the API, and displays the extracted text while offering download options for any inline data returned.

## Features

- **Image Upload & Clipboard Paste:** Upload images via file selection or paste directly from your clipboard.
- **Multiple Model Options:** Choose between different Gemini models:
  - gemini-2.0-flash
  - gemma-3-27b-it
  - gemini-2.5-pro-preview-03-25
- **Modal Image Preview:** Click on image thumbnails to view a larger preview.
- **Downloadable Output:** If the API response includes inline data, downloadable links are provided.
- **Simple Chat Interface:** The interface emulates a chat with user, system, and model messages for clear interaction.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, etc.)
- A valid Google Gemini API key. Replace the `apiKey` value in `script.js` with your API key.

### Configuration

- **API Key:** Update the `apiKey` variable in `script.js` with your Google Gemini API key.
- **Model Selection:** Use the dropdown menu in the app to choose your desired model for processing.

## Usage

1. **Open the Application:** Launch the app in your browser.
2. **Upload or Paste an Image:** Use the file input or paste a screenshot directly.
3. **Select the Model:** Choose the appropriate Gemini model from the dropdown.
4. **Perform OCR:** Click the "Perform OCR" button. The image is processed and the extracted text is shown in the chat interface.

## File Structure

- `index.html` – Main HTML file with the user interface and modal image preview.
- `script.js` – JavaScript handling image uploads, OCR requests, and response rendering.


## Demo
https://yapweijun1996.github.io/OCR-Gemini-API-JavaScript/

## Disclaimer

This project is for demonstration purposes only and is not affiliated with Google. Ensure you have the appropriate permissions and valid API keys before using the Google Gemini API in a production environment.
