ChatBot Using IBM Watsonx AI and Streamlit
This is a simple, interactive chatbot application built using Streamlit and IBM Watsonx AI foundation models (Granite-13b-instruct-v2). It takes user input and dynamically responds using IBM's AI model, simulating a chat-like experience directly from the browser.


🚀 Features
Interactive UI using Streamlit

Real-time responses powered by IBM Watsonx AI

Chat history persistence with st.session_state

Professionally styled for production-like usage

Uses granite-13b-instruct-v2 – a powerful instruction-following LLM

🛠️ Technologies Used
Python 🐍

Streamlit 🧊

IBM Watsonx AI 🤖

IBM Cloud SDK

📁 Folder Structure
bash
Copy
Edit
.
├── chatbot.py          # Main Streamlit app
├── screenshot.png      # UI Screenshot (optional for GitHub preview)
└── README.md           # Project documentation
🧪 How to Run the Project
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/yourusername/ibm-watsonx-chatbot.git
cd ibm-watsonx-chatbot
2. Install Dependencies
bash
Copy
Edit
pip install streamlit ibm-watsonx-ai
3. Add Your IBM Credentials
Update the api_key, project_id, and base_url inside chatbot.py:

python
Copy
Edit
api_key = "your_api_key"
project_id = "your_project_id"
base_url = "https://your_region.ml.cloud.ibm.com"
4. Run the App
bash
Copy
Edit
streamlit run chatbot.py
🔐 Note on API Key Security
Do not expose your API key in public repositories. Use .env files or Streamlit secrets management in production.

📸 Screenshot
<img src="screenshot.png" width="700"/>
