# 🎥 YouTube Q&A Bot  

An interactive AI tool that lets you **ask questions about any YouTube video** using its transcript. Built with **LangChain, Gradio, YouTube Transcript API, and TinyLlama/Qwen embeddings**.  

---

## 🚀 Features  
- Extracts video transcripts automatically from YouTube  
- Uses LLM + embeddings to answer questions about the content  
- Simple **chatbot-like UI** built with Gradio  
- Works with any video that has subtitles enabled  

---

## 📦 Installation  

Clone the repo:  
git clone https://github.com/username/youtube-qa-bot.git
cd youtube-qa-bot



Create a virtual environment (recommended):  
python -m venv venv

On Linux/Mac
source venv/bin/activate

On Windows
venv\Scripts\activate



Install dependencies:  
pip install -r requirements.txt


---

## ▶️ Usage  

Run the app:  
python app.py




Or if running inside Jupyter/Colab:  
streamlit run app.py


---

## 🛠️ Tech Stack  
- LangChain – for chaining LLM + embeddings  
- Gradio – chatbot-like UI  
- YouTube Transcript API – fetch video transcripts  
- TinyLlama – lightweight LLM  
- Qwen Embeddings – for vector search  

---

## 📌 Example  
1. Enter a YouTube Video ID (e.g., `dQw4w9WgXcQ`)  
2. Ask: *"Who is speaking in this video?"*  
3. Get instant AI-powered answers based on the transcript  

---

## 📄 License  
This project is licensed under the MIT License.  

---

💡 *Contributions are welcome! Feel free to fork and improve.*  
