# Food Ordering Chatbot

This project is a simple AI-powered chatbot for food ordering, built with Python and deployed with a web frontend. It uses NLP to understand user queries and helps users place food orders interactively.

## Features
- Natural language understanding for food ordering
- Interactive chat interface
- Trained model using intents and responses
- Web-based frontend for user interaction

## Project Structure
- `app.py`: Main Flask application
- `chat.py`: Chatbot logic
- `model.py`: Neural network model
- `nltk_utils.py`: NLP utilities
- `train.py`: Model training script
- `intents.json`: Intents and responses data
- `data.pth`: Trained model weights
- `standalone-frontend/`: Frontend files (HTML, CSS, JS)
- `static/`, `templates/`: Web assets and templates

## Setup Instructions
1. Clone the repository:
   ```powershell
   git clone https://github.com/LABGIT-1004/Food-Ordering-Chatbot.git
   ```
2. Install Python dependencies:
   ```powershell
   pip install -r requirements.txt
   ```
3. Train the model (if needed):
   ```powershell
   python train.py
   ```
4. Run the application:
   ```powershell
   python app.py
   ```
5. Access the chatbot via your browser at `http://localhost:5000`

## Requirements
- Python 3.8+
- Flask
- PyTorch
- NLTK

## Usage
- Start the server and interact with the chatbot through the web interface.
- The chatbot will respond to food ordering queries and guide users through the process.

## License
This project is licensed under the MIT License.
