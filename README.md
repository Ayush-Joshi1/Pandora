
End-to-End Intelligent Sales Automation for SMBs 
Team Name: UNORTHODOX 
Team Members: 
•	[Ayush Joshi]
•	[Amit Bhosale]
•	[Abhishek Bochare]
•	[Padmaksh Apsingekar]
________________________________________
Problem Statement
Small and Medium-sized Businesses (SMBs) currently face a massive productivity gap:
•	Time Loss: 15–20 hours per week are lost on manual data entry and repetitive administrative tasks.
•	Human Error: Manual processes are prone to inconsistencies and errors in order processing.
•	Speed: Lead response and quotation times are slow, leading to missed opportunities.
Solution Approach
We have built an AI-powered unified system designed to manage the complete sales lifecycle automatically.
•	AI Workflow Hub: An event-driven execution engine with adaptive conditional paths that "thinks" through the process.
•	Intelligent Routing: The system extracts sender info, cleans data, and identifies customer intent.
•	Automation: It handles everything from inventory checks to generating out-of-stock emails and order confirmations without human intervention.
Tech Stack
•	Workflow Engine: n8n 
•	Artificial Intelligence: OpenAI GPT 
•	Data Management: Google Sheets 
•	Communication: Gmail 
Features
•	Instant Processing: Executes complex workflows in just 6–10 seconds.
•	Automation Suite: Handles orders, invoices, and quotations automatically.
•	Sentiment Monitoring: Monitors customer sentiment to proactively reduce churn.
•	Real-time Analytics: Provides instant sales intelligence and performance insights.
•	Reliability: Built-in retry logic and robust error management for production-level reliability.
Installation Steps
1.	Clone the Repository:
Bash
git clone https://github.com/Ayush-Joshi1/Pandora.git
2.	Setup n8n: Install n8n locally or use a cloud instance.
3.	Import Workflows: Import the provided .json workflow files into your n8n instance.
4.	Configure Credentials: Add your OpenAI API Key, Google Sheets credentials, and Gmail OAuth2 credentials in n8n.
How to Run
1.	Activate Workflows: Ensure all nodes in the n8n dashboard are set to "Active."
2.	Trigger the System: Send a sales inquiry or order request to the configured Gmail address.
3.	Monitor Progress: Watch the real-time execution in the n8n canvas and check the Google Sheet for automated data entry.
Future Scope
•	Advanced Analytics: Developing a dedicated dashboard for deeper business intelligence.
•	Enterprise Integration: Scaling to include CRM integrations like Salesforce and HubSpot.
•	Predictive AI: Implementing AI-powered demand forecasting to optimize inventory.
•	Mobile Access: Building a mobile management application for business owners on the go.
________________________________________
Measurable Impact: Our system delivers a 90% reduction in manual work and 3x faster resolution compared to traditional methods

