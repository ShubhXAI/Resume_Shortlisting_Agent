# Resume_Shortlisting_Agent
he Idea: 💡
To create an autonomous agent that analyzes a resume for a specific role (like a Data Scientist) and makes an initial screening decision, just like a human expert would.

How It Works: ⚙️

📄 PDF Ingestion: The agent takes any resume in PDF format as its input.

🧠 Intelligent Analysis: It uses a powerful LLM (LLaMA-3 via Groq) guided by a detailed system prompt that defines the "ideal candidate" profile and evaluation rules.

🎯 Structured Decisions with LangGraph: The core of the project is a LangGraph workflow. An intelligent router node analyzes the resume and makes a structured, reliable decision to either Shortlist, Escalate, or Reject the candidate.

✅ Actionable Output: The system provides a clear, final recommendation, allowing recruiters to focus only on the most promising applicants.

This project uses Python, LangChain, and LangGraph to build a robust and efficient workflow for a smarter hiring pipeline.
