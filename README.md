## Paris Tour Guide Chatbot <br> 
This project implements a simple multi-turn chat bot using OpenAI's GPT-3.5-turbo model. The bot acts as a Paris tour guide, maintaining conversation context across multiple interactions by storing the conversation history. The bot can handle user inputs and generate relevant responses in a coherent manner.<br>

### Features
*Multi-turn Conversations*: Maintains context across multiple turns of conversation.<br>
*Role-based Messaging*: Uses role-based messages to distinguish between system instructions, user inputs, and assistant responses.<br>
*Contextual Responses*: Generates responses based on the entire conversation history.<br>
### How It Works
System Initialization: The conversation is initialized with a system message that sets the role of the assistant as a Paris tour guide.<br>
User Input Handling: The bot takes user input, appends it to the conversation history, and sends the entire history to the OpenAI API.<br>
Assistant Response: The bot receives a response from the API, appends it to the conversation history, and prints it out.<br>
Conversation Continuation: This process repeats for each user input, allowing for a continuous and context-aware dialogue.<br>
