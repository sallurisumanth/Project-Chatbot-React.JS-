# Chatbot Project

This is a simple chatbot built using HTML, CSS, and React. The chatbot allows users to interact with a virtual assistant that provides automated responses, flips a coin, and rolls a dice. It uses basic state management and asynchronous functions to communicate with the bot, providing a responsive chat interface.

## Features
- **Interactive Chat Interface**: Users can send messages to the chatbot and receive automated responses.
- **Coin Flip**: Type "flip a coin" to simulate a coin flip with heads or tails results.
- **Dice Roll**: Type "roll a dice" to simulate a dice roll with a random number between 1 and 6.
- **Responsive Design**: The app is fully responsive, designed to work well on various screen sizes.
- **Real-time Messaging**: The chatbot responds in real-time to user inputs.
- **Loading Spinner**: Displays a loading spinner while the bot is processing the user's message.

## Technologies Used
- **HTML**: Structure of the page and layout.
- **CSS**: Styling and layout for the chat components.
- **React**: Used for building the dynamic UI, handling state, and managing the conversation flow.
- **JavaScript (Babel)**: Used for asynchronous message handling and DOM manipulation.
- **Chatbot API**: Custom chatbot response logic.

## Getting Started

To run this project locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/your-username/chatbot-project.git
```

### 2. Navigate into the project directory
```bash
cd chatbot-project
```

### 3. Open the `index.html` file in your browser

Simply open the `index.html` file in any modern browser to view the chatbot interface.

## Project Structure
```
chatbot-project/
├── index.html         # Main HTML file
├── styles.css         # CSS file for styling
├── script.js          # JavaScript file containing logic for handling chat
└── images/            # Folder containing images (e.g., user and robot avatars)
```

## Components

- **ChatInput**: Handles user input and sends the message to the chatbot.
- **ChatMessage**: Displays messages from the user and the bot.
- **ChatMessages**: A container that holds all the chat messages.
- **App**: The main component that renders the entire chatbot interface and manages state.

## How It Works
- When a user types a message and presses **Enter** or clicks the **Send** button, the message is added to the chat.
- The message is then sent to the chatbot for processing, and the bot responds asynchronously.
- A loading spinner is displayed while the chatbot is processing the message.
- The chatbot's response is displayed in the chat window.

### Special Commands
- **"flip a coin"**: The bot will simulate a coin flip and respond with either "Heads" or "Tails".
- **"roll a dice"**: The bot will simulate a dice roll and respond with a random number between 1 and 6.

## Example Interaction
1. **User**: "flip a coin"
2. **Bot**: "Heads!"

1. **User**: "roll a dice"
2. **Bot**: "You rolled a 4!"

## Contributing
Feel free to fork this repository and create pull requests if you'd like to improve or add more features. If you encounter any issues or have questions, feel free to open an issue.

## License
This project is open-source and available under the [MIT License](LICENSE).

---

Let me know if this works for you or if you'd like further adjustments!
