# copybot-me
CopyBot Assistant

This is a Flask-based web application that uses the OpenAI API to provide a chat interface to interact with the GPT-3.5-turbo model. Users can ask questions or provide prompts, and the assistant will generate a response using the GPT-3.5-turbo model.

Installation

Ensure you have Python 3.7+ installed on your system.

Install the required packages using pip:

bash

  pip install -r requirements.txt

Set your OpenAI API key as an environment variable:
bash

  export OPENAI_API_KEY="your_api_key_here"

Replace your_api_key_here with your actual API key.

Running the Application
Start the Flask development server:

  python app.py

Access the web interface by opening a web browser and navigating to http://127.0.0.1:8080.

Usage
Enter a message or prompt in the input field.

Adjust the parameters (engine, temperature, frequency penalty, max tokens) as needed.

Click "Send it!" to submit the message and receive a response from the GPT-3.5-turbo model.

License
This project is licensed under the Apache 2.0 License. See the LICENSE file for details.

Disclaimer
This application is a demonstration and should not be used in production environments. Always follow OpenAI's usage guidelines and ensure proper security measures are in place when using the API.
