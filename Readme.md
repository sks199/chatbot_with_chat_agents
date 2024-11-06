## Overview

This Google Colab notebook, implements a chatbot that facilitates conversations and processes images. The conversation history and image processing results are sent to CrewAI agents to obtain a second specialist opinion, enhancing the chatbot's effectiveness in providing informed responses.

## Features

- **Interactive Chatbot**: Engage in a conversation with the chatbot.
- **Image Processing**: Upload images for processing and analysis.
- **Expert Consultation**: Automatically send conversation history and image results to CrewAI agents for additional insights.

## Requirements

To run this notebook, you will need:

- A Google account to access Google Colab.
- Basic understanding of Python programming.
- Internet access for sending requests to CrewAI.

## Usage Instructions

1. **Open the Notebook**: Click on the link provided to open the notebook in Google Colab.
2. **Set Up Environment**: Run the initial setup cells to install any necessary libraries.
3. **Start a Conversation**:
   - Input your message in the provided text box.
   - Press "Enter" or click the "Send" button to submit your message.
4. **Upload Images**: If you wish to process an image, use can upload when the chatbot starts running.
5. **Receive Specialist Opinion**: After completing your conversation or image submission, the results will be sent to CrewAI agents, and you will receive feedback accordingly.

## Code Structure

- **Cell 1**: Import necessary libraries and set up configurations.
- **Cell 2**: Define functions for chatbot interaction and image processing.
- **Cell 3**: Implement the main chatbot loop for user interaction.
- **Cell 4**: Handle image uploads and processing logic.
- **Cell 5**: Send conversation history and image processing results to CrewAI agents and retrieve responses.


