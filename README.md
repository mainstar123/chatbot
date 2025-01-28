# Chatbot Project

This is a Python-based chatbot project that uses OpenAI's GPT-4 model to simulate a helpful assistant in a clothes store. The assistant encourages customers to try items that are on sale.

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/chatbot.git
   cd chatbot
   ```

2. Install `pipenv` if you haven't already:

   ```sh
   pip install pipenv
   ```

3. Create a virtual environment and install the required packages:

   ```sh
   pipenv install
   ```

4. Activate the virtual environment:

   ```sh
   pipenv shell
   ```

5. Create a `.env` file in the project root and add your API keys:
   ```env
   OPENAI_API_KEY=your_openai_api_key
   ANTHROPIC_API_KEY=your_anthropic_api_key
   GOOGLE_API_KEY=your_google_api_key
   ```

## Usage

Run the main script to start the chatbot:

```sh
python main.py
```

The chatbot will launch a Gradio interface where you can interact with it.

## Project Structure

```
chatbot/
│
├── main.py          # Main script to run the chatbot
├── Pipfile          # Pipenv dependencies
├── Pipfile.lock     # Pipenv lock file
└── .env             # Environment variables (not included in the repository)
```

## License

This project is licensed under the MIT License.
