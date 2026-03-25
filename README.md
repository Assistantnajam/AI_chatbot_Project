# AI_chatbot_Project
A Python-powered WhatsApp automation bot that uses PyAutoGUI for screen interaction and OpenAI's GPT-3.5 to generate humorous, context-aware "roasts" and replies. Features real-time message monitoring and intelligent sender detection.


# AI-Powered WhatsApp Auto-Responder 

## Project Overview
The system functions by simulating human mouse and keyboard actions to capture chat history and then processes it using AI.

* **Coordinate Mapping:** Uses a dedicated script to identify precise screen locations for UI elements.
* **Automated Interaction:** Emulates clicking, dragging to select text, and keyboard shortcuts to copy chat logs.
* **Logic-Based Triggering:** Checks the chat log to see if the last message came from a specific sender before responding.
* **AI Persona:** Integrates with the OpenAI API to adopt a specific persona—a Pakistani coder named Najam.

---

## Technical Stack
* **Language:** Python
* **Automation:** PyAutoGUI for cursor movement and click events
* **AI Engine:** OpenAI GPT-3.5-turbo for natural language generation
* **Clipboard Management:** Pyperclip for handling text transfer between the script and the chat window
* **Dependencies:** Includes `pydantic`, `httpx`, and `PyGetWindow` for stability.

---

## File Descriptions
* [cite_start]**01_get_cursor.py:** A utility script used to calibrate the bot by printing live X and Y coordinates. [cite: 1]
* **03_bot.py:** The main script that runs the automation loop and generates AI responses.
* **key.py:** A configuration file for storing your OpenAI API key safely.
* **requirements.txt:** A list of all libraries needed to run this project.
  
