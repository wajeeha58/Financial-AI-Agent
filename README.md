## Financial AI Agent

📌 Overview

The Financial AI Agent is an advanced AI-powered financial assistant that helps analyze stock market data, fetch real-time financial insights, and search the web for relevant financial news. It leverages:

Groq's Llama 3 Model for AI processing

YFinanceTools for stock market data

DuckDuckGo for web searches

This agent can be used to fetch stock prices, analyst recommendations, company news, and more.

🚀 Features

✅ AI-driven financial insights✅ Real-time stock market data analysis✅ Web search for financial news✅ Data displayed in structured tables

🛠️ Setup Instructions

1️⃣ Clone the Repository

git clone https://github.com/wajeeha58/Financial-AI-Agent.git

2️⃣ Install Dependencies

Ensure you have Python 3.8+ installed, then run:

pip install -r requirements.txt

3️⃣ Set Up Environment Variables

Create a .env file in the project root and add your API key:

PHI_API_KEY=your_phi_api_key_here

4️⃣ Run the AI Agents

Run the following script to start using the agents:

python main.py

🏦 Usage Examples

You can run the financial agent to fetch stock details like:

print(finance_agent.run("AAPL stock price and fundamentals"))

Or use the web search agent:

print(web_search_agent.run("Latest AI advancements in finance"))

🤝 Contributing

Want to improve this project? Feel free to fork the repository, make changes, and submit a pull request! 🚀

📜 License

This project is licensed under the MIT License.
