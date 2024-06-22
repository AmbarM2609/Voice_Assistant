
# Voice Assistant Project

This repository showcases a comprehensive voice-controlled assistant developed using Python. The assistant leverages speech recognition, text-to-speech conversion, web scraping, email automation, and translation services to perform a variety of tasks based on user voice commands.

## Features

### 1. Speech Recognition
- Captures and recognizes spoken words using the `speech_recognition` library.
- Converts spoken words to text with Google's speech recognition service.

### 2. Text-to-Speech
- Provides auditory feedback using the `pyttsx3` library.
- Customizable voice properties for a personalized experience.

### 3. Wikipedia Search
- Fetches summaries of spoken topics using the `wikipedia` library.
- Reads out the fetched summaries for user convenience.

### 4. News Retrieval
- Retrieves the latest news articles using the `GoogleNews` library.
- Commands include "headlines," "tech," "politics," "sports," and "cricket" for specific news categories.

### 5. Email Automation
- Automates email sending using the `yagmail` library.
- Captures speech input, converts it to text, and sends it as an email message.

### 6. Command Execution
- Executes a variety of commands such as opening Google Chrome, announcing the current time, playing YouTube videos, and opening the YouTube website.
- Uses `subprocess` for opening applications and `pywhatkit` for playing YouTube videos.

### 7. Language Translation
- Translates recognized text into different languages using the `google_trans_new` library.
- Captures speech input, recognizes text, and translates it before reading it out loud.

## Installation

### Prerequisites
- Python 3.6 or higher
- Required Python libraries:
  - `speech_recognition`
  - `wikipedia`
  - `pyttsx3`
  - `GoogleNews`
  - `yagmail`
  - `pywhatkit`
  - `webbrowser`
  - `google_trans_new`

### Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/AmbarM2609/Voice_Assistant.git
    cd voice-assistant-project
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the scripts:
    ```bash
    python script_name.py
    ```

## Usage

### Wikipedia Search
- Run the script `wikipedia_search.py` to search for topics on Wikipedia and get summaries read out loud.

### News Retrieval
- Run the script `news_retrieval.py` to fetch and listen to the latest news articles in various categories.

### Email Automation
- Run the script `email_automation.py` to capture speech input and send it as an email message.

### Command Execution
- Run the script `command_execution.py` to execute commands such as opening Chrome, getting the current time, playing YouTube videos, and more.

### Language Translation
- Run the script `language_translation.py` to capture speech, recognize text, and translate it into a specified language.

## Example Commands
- "Open Chrome"
- "What time is it?"
- "Play [song name] on YouTube"
- "Get me today's headlines"
- "Translate to Spanish"

## Demonstration

Here's a quick demonstration of how to use the voice assistant:

### Running the Wikipedia Search Script
```bash
python wikipedia_search.py
```
- Speak a topic when prompted.
- The assistant will fetch and read out the Wikipedia summary.

### Running the News Retrieval Script
```bash
python news_retrieval.py
```
- Speak a news category such as "headlines" or "tech."
- The assistant will fetch and read out the latest news articles.

### Running the Email Automation Script
```bash
python email_automation.py
```
- Speak your message when prompted.
- The assistant will send the message as an email.

### Running the Command Execution Script
```bash
python command_execution.py
```
- Speak a command such as "Open Chrome" or "What time is it?"
- The assistant will execute the command.

### Running the Language Translation Script
```bash
python language_translation.py
```
- Speak a phrase when prompted.
- Type the target language when asked.
- The assistant will translate and read out the phrase.

## Conclusion

This Voice Assistant Project demonstrates the powerful capabilities of integrating various Python libraries to create a versatile and user-friendly voice-controlled assistant. Whether you need to search Wikipedia, get the latest news, send emails, execute commands, or translate languages, this assistant is ready to help!

Enjoy using your voice assistant!

---
