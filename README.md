CryptoBuddy - Cryptocurrency Investment Advisor Chatbot
A friendly rule-based chatbot that provides educational cryptocurrency investment advice with both command-line and web interfaces.

Features
Interactive Chat Interface: Beautiful web interface with real-time chat functionality
Investment Disclaimer: Proper risk awareness and educational disclaimers
Cryptocurrency Data: Predefined database with Bitcoin, Ethereum, and Cardano information
Live Data Integration: Optional CoinGecko API integration for real-time prices
Natural Language Processing: NLTK-powered text processing for better user interaction
Rule-Based Advice: Responds to queries about:
Trending cryptocurrencies
Sustainable and eco-friendly coins
Energy-efficient cryptocurrencies
Long-term investment recommendations
Specific cryptocurrency information
Project Structure
├── app.py                 # Flask web application
├── main.py               # Command-line interface
├── chatbot.py            # Main chatbot logic
├── crypto_data.py        # Cryptocurrency database and utilities
├── nlp_utils.py          # Natural language processing
├── api_client.py         # CoinGecko API client
├── templates/
│   └── index.html        # Web interface template
└── README.md
Installation
Install required dependencies:
pip install flask nltk requests
Run the web application:
python app.py
Or run the command-line version:
python main.py
Usage
Web Interface
Open your browser to http://localhost:5000
Click on sample questions or type your own
Get friendly cryptocurrency advice with emojis
Command Line
Run python main.py
Type questions about cryptocurrency investments
Type 'bye' or 'exit' to quit
Sample Questions
"Which crypto is trending?"
"What's the most sustainable coin?"
"Which crypto should I invest in for long-term growth?"
"Which coins use less energy?"
"Tell me about Bitcoin"
Disclaimer
This chatbot provides educational information only and should NOT be considered as financial advice. Cryptocurrency investments are highly volatile and risky. Always do your own research and consult with qualified financial advisors.

Technology Stack
Backend: Python, Flask
Frontend: HTML, CSS, JavaScript
NLP: NLTK
API: CoinGecko (optional)
Data: Predefined cryptocurrency database
Author
Built with Python and designed for educational cryptocurrency investment guidance.

CryptoBuddyAssistant - Replit
