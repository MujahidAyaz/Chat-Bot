# DialoGPT Chatbot

This project demonstrates how to create an interactive chatbot using the pre-trained **DialoGPT** model by Microsoft. Built with the Hugging Face `transformers` library, this chatbot can generate natural, human-like responses based on user input. It is designed to be simple to use and can be easily run in Google Colab.

## Features

- **Conversational AI**: Engage in a conversation with the chatbot, and it will generate creative responses.
- **Pre-trained DialoGPT Model**: Uses Microsoft's **DialoGPT-medium** model, which is fine-tuned for generating dialogue.
- **Google Colab Ready**: The code is set up to run directly in Google Colab, making it easy for anyone to use without complex setup.

## Requirements

Before running the project, ensure you have the following:

- Python 3.x
- [Google Colab](https://colab.research.google.com/) (recommended for easy setup and execution)
- Hugging Face `transformers` library

## Setup Instructions

### Option 1: Running on Google Colab

The easiest way to run this project is in [Google Colab](https://colab.research.google.com/), which provides an interactive environment and pre-configured libraries.

1. Open [this notebook](https://colab.research.google.com/).
2. Upload the notebook file from this repository.
3. Run the cells sequentially to start interacting with the chatbot.

### Option 2: Running Locally

To run the chatbot on your local machine:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/dialoGPT-chatbot.git
    cd dialoGPT-chatbot
    ```

2. **Install dependencies**:
    ```bash
    pip install transformers
    ```

3. **Run the Python script**:
    ```bash
    python chatbot.py
    ```

This will start the chatbot in the terminal where you can type your messages and interact with it.

## How to Use

1. After running the notebook or script, the chatbot will be ready to interact with you.
2. Type your message and hit enter, and the chatbot will generate a response.
3. To end the conversation, simply type `exit`, `quit`, or `bye`.

### Example Interaction

Chatbot is ready! Type 'exit' to quit. You: Hello! Chatbot: Hello! How can I assist you today? You: What's the weather like today? Chatbot: I can't check the weather, but it’s a good day for a chat! You: exit Chatbot: Goodbye!


## Model Information

The chatbot is powered by **DialoGPT-medium**, a conversational model fine-tuned from GPT-2 by Microsoft. You can learn more about DialoGPT and its capabilities on the [Hugging Face Model Page](https://huggingface.co/microsoft/DialoGPT-medium).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements

- **Hugging Face** for providing the `transformers` library and pre-trained models.
- **Microsoft** for developing DialoGPT.

## Contact

If you have any questions or suggestions, feel free to reach out via mujahid.ayaz1@gmail.com .

