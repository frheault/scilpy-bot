# Scil-Chatbot

A chatbot to help you navigate the Scilpy library. This tool is designed to answer your questions about Scilpy, a Python library for diffusion MRI and tractography processing.

## Installation

To install the Scilpy-Bot for development, clone the repository and install it in editable mode:

```bash
git clone https://github.com/scilus/scil_chatbot.git
cd scil_chatbot
pip install -e .
```

## Dependencies

The chatbot relies on the following libraries:

*   [scilpy](https://github.com/scilus/scilpy)
*   [openai](https://pypi.org/project/openai/)
*   [google-generativeai](https://pypi.org/project/google-generativeai/)

For information on how to generate the Scilpy documentation, please refer to the [official documentation](https://scilpy.readthedocs.io/en/latest/).

## Usage

Once installed, you can start the chatbot by running:

```bash
scil_chatbot
```

## Tips for Interacting with the Chatbot

To get the most out of the Scilpy-Bot, here are a few tips:

*   **Be specific:** Instead of asking "How do I use scilpy?", ask "How can I use scilpy to perform tractography on a DWI dataset?".
*   **Provide context:** If you are encountering an error, provide the full error message and the code snippet that is causing the error.
*   **Ask for examples:** If you are unsure how to use a specific function, ask for a code example.
*   **Keep it simple:** Ask one question at a time. This will help the chatbot to provide a more focused and accurate response.