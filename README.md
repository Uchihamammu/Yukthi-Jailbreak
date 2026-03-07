# Sentinel-X Cyber-Logic Challenge 🕵️‍♂️

Sentinel-X (also known as the Jailbreak Challenge) is a multi-stage interactive web application built with Python and Streamlit. It is designed as a progressive logic and social engineering game.

### 🚀 Features
* **Spot Registration System:** Captures user details (Name, Email, Phone, College) to track progress.
* **Stage 1 - Social Engineering:** An interactive AI chatbot powered by the Groq API (`llama-3.1-8b-instant`), requiring users to use conversational logic to progress.
* **Stage 2 - Code Breaker:** A logic puzzle where users must crack a multi-digit hidden PIN.
* **Stage 3 - The Final Hunt:** A physical/digital treasure hunt system utilizing specific unlock codes (e.g., ALPHA-77).
* **Live Leaderboard:** An auto-refreshing dashboard that tracks user progress across all stages in real-time.

### 💻 Tech Stack
* **Language:** Python
* **Frontend/Framework:** Streamlit
* **AI Integration:** Groq API

### ⚙️ How to Run Locally
1. Clone the repository: `git clone https://github.com/Uchihamammu/[Your-Repo-Name].git`
2. Navigate to the directory: `cd [Your-Repo-Name]`
3. Install dependencies: `pip install streamlit groq`
4. Run the application: `streamlit run app.py` (Replace 'app.py' with your main file name).
*Note: You will need your own Groq API key to run Stage 1.*
