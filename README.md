# Content Researcher & Writer

This is an AI-powered Streamlit application that uses [CrewAI](https://docs.crewai.com/) to automate content research and writing through a team of intelligent agents. Simply input a topic and let two agents (a Research Analyst and a Content Writer) generate a detailed, properly cited blog post.

---

## Features

- Research agent fetches accurate and up-to-date content
- Writing agent turns research into well-structured blog articles
- Outputs Markdown format with headings, links, and references
- Customizable prompt temperature
- One-click download of generated content

---

## Powered By

- [CrewAI](https://github.com/joaomdmoura/crewAI)
- [LangChain LLMs](https://docs.langchain.com/)
- [Streamlit](https://streamlit.io/)
- [Serper.dev](https://serper.dev/) (search tool)

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Create & Activate Virtual Environment

```bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Create .env File

Create a `.env` file in the root directory and add your keys:

```env
GEMINI_API_KEY=your_gemini_api_key
SERPER_API_KEY=your_serper_api_key
```

---

## ▶️ Run the App

```bash
streamlit run streamlit_app.py
```

- Enter a topic in the sidebar
- Adjust the temperature slider (for creativity level)
- Click **Generate Content** button
- View the result and download as a markdown file for use
---

## Example Topics

- "The future of renewable energy"
- "AI in healthcare"
- "Why remote work is here to stay"

---
