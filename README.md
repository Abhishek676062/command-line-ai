# Text Summarizer CLI

This is a command-line interface (CLI) tool that summarizes text using the Qwen2 0.5B model via Ollama. It can summarize text from a file or directly from command-line input.

## Features

- Summarize text from a file
- Summarize text directly input through the command line
- Uses Ollama API with Qwen2 0.5B model for summarization
- Built with Python and Click library for CLI functionality

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.6 or higher installed
- Ollama installed and running on your system
- Qwen2 0.5B model pulled in Ollama

## Installation

1. Clone this repository:
   git clone https://github.com/Abhishek676062/command-line-ai.git
   cd command-line-ai.git
   Copy
2. Install the required Python packages:
   pip install -r requirements.txt
   Copy
3. Ensure Ollama is installed and the Qwen2 0.5B model is available:
   ollama pull qwen2:0.5b
   Copy

## Usage

To summarize text from a file:
python summarizer.py -t path/to/your/file.txt
Copy
To summarize text directly from the command line:
python summarizer.py "Your text goes here. It can be multiple sentences."
Copy

## Example

$ python summarizer.py "The quick brown fox jumped over the lazy dog. This sentence is used to demonstrate typing and display text in many languages."

Summary: This text describes a common pangram used to showcase fonts and typing skills, featuring a quick fox jumping over a lazy dog.

Copy

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License

[MIT License](LICENSE)

## Acknowledgments

- Ollama for providing the API to run AI models locally
- Qwen2 0.5B model developers
- Click library for simplifying CLI creation in Python
