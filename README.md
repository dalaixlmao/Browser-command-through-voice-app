# Browser-command-through-voice-app

This web application allows users to convert their speech into text and use it to generate Selenium code for browser automation. The application captures the user's voice input, processes it into text using the Whisper API for speech recognition, and sends it to a chatbot powered by OpenAI's ChatGPT. The chatbot generates Selenium code based on the user's command, which is then automatically executed in the browser to perform the desired operation.

## Features

- Converts speech to text using the Whisper API for speech recognition
- Generates Selenium code based on user commands
- Executes Selenium code in the browser for browser automation
- Provides real-time feedback of spoken text
- User-friendly interface with a simple "Tap to Speak" button

## Prerequisites

- Modern web browser with support for the Whisper API
- Internet connection
- Whisper API credentials 
- ChatGpt API credentials

## Usage

1. Set up your Whisper API credentials by following the instructions provided by OpenAI (insert link to OpenAI's documentation).
2. Open the web application in your web browser.
3. Click the "Tap to Speak" button.
4. Speak your command clearly into the microphone.
5. The spoken text will appear in the designated area on the screen.
6. The generated Selenium code will be executed automatically in the browser, performing the desired operation.

## Technologies Used

- HTML
- CSS
- JavaScript
- Whisper API (OpenAI)
- Selenium WebDriver
- OpenAI ChatGPT

## Development

To set up the development environment and run the application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/dalaixlmao/Browser-command-through-voice-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd speech-to-text-app
   ```
   
3. Update the Whisper API credentials in the appropriate file (update token on line 14 of card.js with your OpenAI key).
   
4. Open the card.html file in your preferred web browser.
