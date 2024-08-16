Headstarter Support Assistant

This is a chatbot application built using Next.js and the OpenAI API. The bot is designed to assist users by providing automated responses to their queries.

Features

Real-time Messaging: Users can interact with the bot and receive real-time responses.
AI-Powered Responses: Powered by OpenAI’s gpt-3.5-turbo for efficient and intelligent conversation.
Material UI Integration: Utilizes Material UI components for a modern and responsive user interface.
Auto-Scroll to Bottom: The chat automatically scrolls to the latest message.
Loading State: Indicates when a message is being processed.
Installation

To get started with the project locally, follow these steps:

Clone the repository:
bash
Copy code

git clone https://github.com/yourusername/headstarter-support-assistant.git

cd headstarter-support-assistant

Install dependencies:

bash

npm install

Create a .env.local file in the root directory with the following content:

makefile



OPENAI_API_KEY=your_openai_api_key
Run the development server:

npm run dev
Open http://localhost:3000 in your browser to see the application in action.
Usage

Send a message: Type your message into the input box and press Enter or click the "Send" button. The bot will process your input and provide a response.
Error Handling: If an error occurs, the bot will inform you and ask you to try again.
API Reference

Endpoint: /api/chat
Method: POST
Body: JSON array containing the conversation history.
Response: A streaming response from OpenAI's API, processed in real-time.
Troubleshooting

Model Errors: Ensure that the correct OpenAI model is specified in your API request. Currently, the application is set up to use gpt-3.5-turbo.
Environment Variables: Double-check that your OpenAI API key is correctly set in the .env.local file.
License


Acknowledgements

OpenAI for providing the GPT models.
Material UI for the UI components.
Next.js for the robust framework.
