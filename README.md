# 🎥 YouTube Video Analyzer

An AI-powered YouTube Video Analyzer built using **Python, Streamlit, Agno, and Groq**. This application helps users analyze YouTube videos, understand their content, and extract meaningful insights using AI.

## 🚀 Live Demo

**Try the application here:**

👉 https://youtube-video-analyzer-77.streamlit.app/

## ✨ Features

- 🎬 **YouTube Video Analysis:** Analyze YouTube videos using their URLs.
- 🧠 **AI-Powered Insights:** Use an AI agent to understand video content.
- 📝 **Video Summarization:** Generate concise summaries of video content where transcript access is available.
- 💬 **Interactive Experience:** Interact with the analyzer through a simple Streamlit interface.
- ⚡ **Groq Integration:** Leverage Groq-supported language models for AI-powered analysis.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Frontend:** Streamlit
- **AI Agent Framework:** Agno
- **LLM Provider:** Groq
- **Video Source:** YouTube
- **Environment Management:** python-dotenv

## 📂 Project Structure

```text
youtube-video-analyzer/
├── ui.py
├── youtube_analyzer.py
├── requirements.txt
├── .gitignore
├── README.md
└── LICENSE
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Danish-khan77/youtube-video-analyzer.git
cd youtube-video-analyzer
```

### 2. Create a Virtual Environment (Optional)

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the project root directory and add your Groq API key:

```env
GROQ_API_KEY=your_groq_api_key
```

Get your API key from the [Groq Console](https://console.groq.com/).

**Security:** Never commit your `.env` file or expose your API key publicly.

### 5. Run the Application

```bash
streamlit run ui.py
```

The application will start locally, and Streamlit will provide a URL in the terminal.

## ☁️ Deployment

This application is deployed using **Streamlit Community Cloud**.

🔗 **Live Application:** https://youtube-video-analyzer-77.streamlit.app/

The Groq API key is configured through Streamlit Cloud Secrets.

## 🔐 Environment Variables

| Variable | Description |
|---|---|
| `GROQ_API_KEY` | API key used to access Groq models |

## 📌 Important Notes

- Video analysis depends on the availability of accessible YouTube transcripts and the capabilities of the configured AI model.
- API usage may be subject to Groq's rate limits and usage policies.
- This project is intended for educational and demonstration purposes.

## 👨‍💻 Author

**Danish Khan**

- GitHub: [@Danish-khan77](https://github.com/Danish-khan77)
- LinkedIn: [Danish Khan](https://linkedin.com/in/danish-khan-cse)

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

⭐ If you find this project useful, consider giving the repository a star!