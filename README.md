# StockSage
StockSage is a powerful financial stock assistant chatbot designed to provide real-time stock analysis and information. This repository contains the source code for the StockSage chatbot, which is built using Python, Streamlit, OpenAI's GPT-3.5 model, and various financial libraries.

# Features
Real-Time Stock Analysis: Get the latest stock price, calculate moving averages, RSI, MACD, and plot stock prices over the last year.
Interactive Conversations: Engage in interactive conversations with the chatbot using natural language to query stock-related information.
Remote Access: The chatbot is accessible remotely through a Streamlit web application, making it convenient for users to use from anywhere.
# How It Works
The StockSage chatbot leverages OpenAI's GPT-3.5 model to interpret user queries and provide relevant responses. The chatbot offers a set of predefined functions for performing various stock analysis tasks, including retrieving stock prices, calculating technical indicators, and plotting stock price charts.

Here's a high-level overview of how the chatbot works:

User Input: Users interact with the chatbot by providing text input through the Streamlit web application.
OpenAI GPT-3.5 Model: The user input is passed to the GPT-3.5 model, which generates responses based on the provided information.
Function Calls: The chatbot recognizes function calls within the user's input and extracts relevant details, such as the function name and arguments.
Data Retrieval and Processing: The chatbot uses various financial libraries, such as yfinance, to retrieve stock data, calculate indicators, and generate charts.
Response Generation: The chatbot generates responses containing stock analysis results, charts, or other relevant information.
Interactive Conversations: The conversation history is maintained to ensure coherent and context-aware interactions between the user and the chatbot.
# Installation and Usage
Clone the repository to your local machine.
Install the required libraries by running pip install -r requirements.txt.
Obtain your OpenAI API key and replace 'YOUR_API_KEY' in the code with your actual API key.
Run the Streamlit app using streamlit run main.py.
Interact with the chatbot through the web interface.
# Supported Functions
The chatbot supports the following functions for stock analysis:

getStockPrice: Get the latest stock price for a given company ticker symbol.
calculateSMA: Calculate the simple moving average for a stock ticker over a specified window.
calculateEMA: Calculate the exponential moving average for a stock ticker over a specified window.
calculateRSI: Calculate the Relative Strength Index (RSI) for a stock ticker.
calculateMACD: Calculate the Moving Average Convergence Divergence (MACD) for a stock ticker.
plotStockPrice: Plot the stock price for the last year for a given company ticker.
Contribution
Contributions to StockSage are welcome! If you have any improvements, bug fixes, or new features to suggest, feel free to open an issue or submit a pull request.
