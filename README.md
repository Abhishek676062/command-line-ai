# Text Summarizer CLI

A powerful command-line tool for summarizing text using the Qwen2 0.5B model via Ollama.

## 🚀 Features

- 📄 Summarize text from a file
- 💬 Summarize text directly from command-line input
- 🤖 Utilizes Ollama API with Qwen2 0.5B model
- 🐍 Built with Python and Click library for robust CLI functionality

## 📋 Prerequisites

Ensure you have the following installed:

- Python 3.6+
- Ollama
- Qwen2 0.5B model (via Ollama)

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Abhishek676062/command-line-ai.git
   cd command-line-ai

Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

Pull the Qwen2 0.5B model:
   ```bash
   ollama pull qwen2:0.5b
   ```


## 📖 Usage
Summarize from a file:
   ```bash
   python summarizer.py -t path/to/your/file.txt
```
Summarize direct input:
   ```bash
   python summarizer.py "Your text goes here. It can be multiple sentences."
```

## 🌟 Example
   ```bash
   python summarizer.py "The quick brown fox jumped over the lazy dog. This sentence is used to demonstrate typing and display text in many languages."
```
   ```bash
   Summary: This text describes a common pangram used to showcase fonts and typing skills, featuring a quick fox jumping over a lazy dog.
```

## 🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## 📄 License
This project is licensed under the MIT License.

## 🙏 Acknowledgments

- Ollama - For the API to run AI models locally
- Qwen2 0.5B model developers
- Click - For simplifying CLI creation in Python


This version of the README:
- Uses emojis to make sections more visually distinctive
- Formats code blocks consistently
- Provides clearer visual separation between sections
- Uses more concise language in some areas
- Adds links to acknowledgments where applicable
