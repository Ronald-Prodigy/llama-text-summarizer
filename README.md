# LLaMA Text Summarizer

A lightweight AI application that uses the **LLaMA** model (via [Ollama](https://ollama.ai)) to summarize text.

## Features
- ⚡ **FastAPI backend** for handling API requests
- 🎨 **Streamlit frontend** for a simple and interactive UI
- 🧠 **Local LLaMA model** running through Ollama for offline AI processing

## Setup

Make sure you already have python installed

1. **Make a new directory - LLaMa text Summarizer**
   ```bash
   mkdir LLaMa text Summarizer
1. **Open terminal on your IDE and create a virtual environment**
   ```bash
    python -m venv venv
    source venv/bin/activate # or venv\Scripts\activate on Windows
1. **Install dependencies**
   ```bash
   pip install fastapi uvicorn streamlit requests python-multipart

1. **Install Ollama**
Ollama is required to run the LLaMA model locally.  
Follow the instructions for your OS:  
- **macOS & Linux** → [Download here](https://ollama.ai/download)  
- **Windows** (Preview) → [Download here](https://ollama.ai/download)  

Verify installation:
```bash
ollama --version
```
**Pull the LLaMA Model**
Run the following to download the LLaMA model:

```bash
ollama pull llama2
```
4. **Start the backend**
   ```bash
   uvicorn backend.main:app --reload
1. **Lauch the frontend**
   ```bash
   streamlit run frontend/app.py

# LLaMA Text Summarizer

A lightweight AI application that uses the **LLaMA** model (via [Ollama](https://ollama.ai)) to summarize text.









   
 