# GenAI Text Summarizer

**GenAI Text Summarizer** is a flexible and modular application that uses generative AI models to summarize text. Users can input content by typing, uploading documents (PDF, DOCX, TXT), or recording audio. The system transcribes and summarizes the input efficiently through a user-friendly web interface built with Gradio.


## 🚀 Features

- **Direct Text Input**: Enter text manually for summarization.
- **File Upload**: Upload `.txt`, `.pdf`, or `.docx` files.
- **Audio Input**: Record or upload audio files to transcribe and summarize.
- **Interactive Interface**: Built using **Gradio** for an intuitive experience.


## 📦 Installation

### Prerequisites

- Python 3.11 or higher
- Virtual environment (optional but recommended)

### Steps

1. **Clone the Repository**

```bash
git clone https://github.com/rrrreddy/genai-text-summarization.git
cd genai-text-summarization
```

2. **Create and Activate Virtual Environment**
```bash
python -m venv .env
source .env/bin/activate  # On Windows: .env\Scripts\activate
```

3. **Installation dependencies**
```bash
pip install -r requirements.txt
```

4. **Install the package locally**
```bash
pip install -e .
```

##To run as a module :
```bash
python -m api.app
```

## 📝 Logging
- Logs are saved at logs/app.log. Check this file for debugging and application status.

## 🤝 Contributing
- Contributions are welcome! Fork the repo and submit a pull request for improvements or fixes.

## 🙏 Acknowledgments
- Thanks to Hugging Face for their transformer models.
- Thanks to Gradio for the clean and easy UI framework.



