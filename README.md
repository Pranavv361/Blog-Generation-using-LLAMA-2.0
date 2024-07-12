# Blog Generation using LLAMA 2.0

## Introduction

This project uses the LLAMA 2 model to generate blog content.
The application provides an interface to input prompts and receive generated text based on those prompts.

## Installation

You will need a LLAMA model .bin file to generate the blog content. Download the LLAMA 2 model from this [URL](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main)

1. **Clone the repository**:

   ```sh
   git clone <repository_url>
   ```

2. **Create and activate a virtual environment**:

   ```sh
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install the required packages**:
   ```sh
   pip install -r requirements.txt
   pip install -U langchain-community
   ```

## Running the Application

1. **Run the application**:

   ```sh
   streamlet run app.py
   ```

2. **Access the application**:
   Open your web browser and go to `http://127.0.0.1:5000` to interact with the blog generation interface.

## LLAMA 2 Model

The project utilizes the LLAMA 2 model for text generation. You can find more information and access the model [here](https://huggingface.co/meta-llama/Llama-2-7b).

## Files

- `app.py`: The main application file.
- `requirements.txt`: Lists the dependencies required to run the application.
- `.gitignore`: Specifies which files and directories to ignore in version control.

## Requirements

- Python 3.7+
- Dependencies listed in `requirements.txt`

## Usage

1. After starting the application, you will see a simple web interface.
2. Enter a prompt in the provided text box.
3. Click the "Generate" button to receive the generated blog content based on your input prompt.
