# Hate Speech Detection App

This Streamlit application uses the OpenAI API to detect hate speech in user-provided text. Below is the code for setting up and running the application.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MSTAM-MDC/hate-speech-detection.git
   cd hate-speech-detection
2.	Install the required packages:
    ```bash
    pip install streamlit openai	

3.	Set up your Streamlit secrets by creating a secrets.toml file in the .streamlit directory with your OpenAI API key:
    ```toml
    [secrets]
    openai_secret = "your_openai_api_key"
	
## Usage
Run the Streamlit app:
    ```bash
    streamlit run app.py

## Features
•	Text area for user input
•	Button to run the hate speech detection
•	Display of results in JSON format
•	Tabs for information about the app, reasons for AI hate speech detection, and contact information

## Contribution
Feel free to contribute to the project by forking the repository and submitting pull requests.
