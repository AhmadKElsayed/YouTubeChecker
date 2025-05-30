# 📺 YouTube Fact Checker  

A real-time fact-checking app for YouTube videos. It extracts factual claims from video transcripts using a Retrieval-Augmented Generation (RAG) Agent and verifies them through three different web search tools, returning verdicts, explanations, and credible URLs — all presented through an interactive Gradio interface.

---

## ✨ Features  

- ✅ Extract YouTube video transcripts  
- ✅ Detect factual claims using Named Entity Recognition (NER)
- ✅ **Context-aware claim windowing**: checks facts within a dynamic sliding window of transcript sentences for better claim validation 
- ✅ Fact-check claims via three web search tools  
- ✅ Return verdicts: ✅ True / ❌ False / ⚠️ Unverifiable  
- ✅ Provide detailed explanations and credible source URLs  
- ✅ User-friendly interface built with Gradio  

---

## 📽️ Demo  

[![Watch the demo](interface.jpg)](https://www.linkedin.com/posts/ahmedkelsayed_aiforgood-factchecking-fightpropaganda-activity-7332074217502310400-OKZT?utm_source=share&utm_medium=member_desktop)

👉 Click the image to see a full demo on LinkedIn!

---

## 🛠️ Tech Stack  

- **Python**  
- **LangChain**  
- **Gradio**  
- **Gemini API**  
- **YouTube Transcript API**  
- **SerpAPI / Google Search API**  
