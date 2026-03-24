AI Financial Coach Agent 💰

A personalized AI-powered financial advisor built using Google's ADK (Agent Development Kit). This application provides in-depth financial analysis, budgeting insights, savings strategies, and debt management recommendations based on your income, expenses, debts, and financial goals.

Features
Multi-Agent Financial Analysis System
Budget Analysis Agent: Analyzes spending patterns and recommends optimizations.
Savings Strategy Agent: Creates personalized savings plans and emergency fund strategies.
Debt Reduction Agent: Provides optimized debt payoff strategies using avalanche and snowball methods.
Expense Analysis
Upload CSV files or manually enter expenses.
Analyze transactions by date, category, and amount.
Visual breakdown of spending by category.
Automated expense categorization and pattern detection.
Savings Recommendations
Emergency fund sizing and building strategies.
Custom savings allocation for multiple goals.
Practical automation techniques for consistent saving.
Progress tracking with milestone recommendations.
Debt Management
Handles multiple debts with interest rate optimization.
Compares avalanche vs. snowball methods.
Visual debt payoff timeline and interest savings analysis.
Actionable debt reduction recommendations.
Interactive Visualizations
Pie charts for expense breakdown.
Bar charts for income vs. expenses.
Debt comparison graphs.
Progress tracking metrics.
Installation & Setup
1. Get a Gemini API Key

Obtain a free API key from Google AI Studio:
Get API Key

Create a .env file in the project root and add your key:

GOOGLE_API_KEY=your_api_key_here
2. Clone the Repository
git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
cd awesome-llm-apps/advanced_ai_agents/multi_agent_apps/ai_financial_coach_agent/
3. Install Dependencies
pip install -r requirements.txt
4. Run the App
streamlit run ai_financial_coach_agent.py
CSV File Format

The application accepts CSV files with the following required columns:

Column	Description	Format
Date	Transaction date	YYYY-MM-DD
Category	Expense category	Text
Amount	Transaction amount (supports currency symbols and commas)	Numeric
Example
Date,Category,Amount
2024-01-01,Housing,1200.00
2024-01-02,Food,150.50
2024-01-03,Transportation,45.00

A template CSV file can also be downloaded directly from the application sidebar.

Technologies Used
Python
Streamlit
Google ADK (Agent Development Kit)
Pandas, NumPy, Matplotlib, Plotly for data processing and visualization
Contribution

Contributions are welcome! Feel free to submit issues or pull requests to improve the AI Financial Coach Agent.
