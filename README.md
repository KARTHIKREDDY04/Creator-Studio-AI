# 🎬 Creator Studio AI

### Intelligent YouTube Content Generation Powered by Google Gemini

Creator Studio AI is an AI-powered web application that transforms simple video ideas into engaging YouTube titles and structured video scripts. Built using Python, Streamlit, Google Gemini, LangChain, and Wikipedia research, it simplifies content creation through an intelligent and user-friendly interface.

## ✨ Features

- 🤖 **AI Title Generation:** Generate creative and engaging YouTube video titles.
- 📝 **Automated Script Writing:** Create structured scripts with hooks, introductions, main content, conclusions, and calls to action.
- 🔎 **Wikipedia Research:** Retrieve relevant background information to support content generation.
- 🎯 **Customizable Content:** Configure narration style, target audience, video duration, and language.
- 🎨 **Professional UI:** Modern dashboard with an intuitive content-generation workflow.
- 📥 **Downloadable Results:** Download generated titles as text files and scripts as Markdown files.
- ⚡ **LLM Integration:** Use Google Gemini through LangChain for AI-powered content generation.
- ☁️ **Google Colab Support:** Run the application in a cloud notebook with a temporary public URL.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Streamlit | Interactive web application |
| Google Gemini API | Language model and content generation |
| LangChain | Prompt engineering and LLM orchestration |
| Wikipedia | Background research |
| Google Colab | Cloud-based execution |
| ngrok | Temporary public access to the application |

## 🏗️ Application Workflow

1. Enter a YouTube video topic.
2. Select the narration style and target audience.
3. Choose the video duration and output language.
4. Retrieve relevant Wikipedia research when enabled.
5. Generate an engaging title using Google Gemini.
6. Generate a complete script using the title and research.
7. Review the output and download the generated content.

## 📸 Application Preview

The application includes three primary output sections:

- **Video Title:** Displays the generated YouTube title.
- **Full Script:** Presents the complete script with structured sections and production suggestions.
- **Research:** Displays the retrieved Wikipedia information.

_Add screenshots of your running application here to showcase the interface._

## 📋 Prerequisites

- Python 3.10 or later recommended
- A Google Gemini API key
- Internet connection
- Google Colab or a local Python environment

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/KARTHIKREDDY04/creator-studio-ai.git
cd creator-studio-ai
```

### 2. Install dependencies

```bash
pip install streamlit langchain-core langchain-google-genai langchain-community wikipedia
```

### 3. Configure the Gemini API key

Generate an API key through [Google AI Studio](https://aistudio.google.com/apikey).

Set the environment variable before starting the application.

**Windows PowerShell:**

```powershell
$env:GOOGLE_API_KEY="YOUR_GEMINI_API_KEY"
```

**Linux or macOS:**

```bash
export GOOGLE_API_KEY="YOUR_GEMINI_API_KEY"
```

Never upload your real API key or other credentials to GitHub.

### 4. Run the application

```bash
streamlit run app.py
```

Open the local URL provided by Streamlit, usually:

`http://localhost:8501`

## 💡 Example

**Input topic:**

How Agentic AI Is Transforming Software Development

**Configuration:**

- Narration style: Professional
- Target audience: Students
- Video duration: 3–5 minutes
- Language: English
- Wikipedia research: Enabled

**Generated output:**

- An engaging YouTube title
- A complete video script
- Structured narration and visual suggestions
- Supporting Wikipedia research
- Downloadable content files

## 🎯 Project Objectives

- Automate repetitive tasks in YouTube content production.
- Explore practical applications of generative AI and large language models.
- Integrate external research into AI-generated content.
- Apply prompt engineering and LLM orchestration with LangChain.
- Build a professional, interactive application using Streamlit.
- Demonstrate the integration of AI services and research tools in a Python application.

## 🔮 Future Enhancements

- Generate multiple title suggestions.
- Create YouTube descriptions, tags, and SEO keywords.
- Generate AI thumbnail prompts.
- Integrate additional research sources and citations.
- Add user authentication and generation history.
- Export scripts to PDF and Word formats.
- Deploy the application to a persistent cloud hosting platform.

## ⚠️ Limitations

- AI-generated content may contain factual inaccuracies.
- Wikipedia retrieval depends on internet connectivity and search relevance.
- Gemini API usage is subject to model availability, quotas, and applicable pricing.
- Google Colab sessions and free ngrok URLs are temporary.
- Generated content should be reviewed before publication.

## 🔐 Security

- Store API keys in environment variables or Streamlit secrets.
- Never commit credentials, tokens, or `.env` files to the repository.
- Use `.gitignore` to exclude sensitive configuration files.
- Restrict access appropriately when deploying the application publicly.

## 👨‍💻 Author

**Karthikeya Reddy Rokkam**

- GitHub: [@KARTHIKREDDY04](https://github.com/KARTHIKREDDY04)

## 📄 License

This project is available for educational and portfolio purposes. If you want to distribute it under the MIT License, add an MIT `LICENSE` file to the repository.

---

⭐ If you find this project interesting, consider starring the repository!

**Creator Studio AI — Turning ideas into video-ready content with generative AI.**
