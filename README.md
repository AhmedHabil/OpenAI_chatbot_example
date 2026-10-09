Requirements:

Python 3.10 or newer
An OpenAI API key
Visual Studio Code (recommended)

Setup InstructionsHow to run the chatbot:
1. Open Visual Studio Code.
2. Open the Chatbot project folder in VS Code.
3. Open the `.env` file in the project folder and add your OpenAI API key:

   OPENAI_API_KEY=put_your_api_key_here

   Keep your API key private. Do not share it or commit the `.env` file.
4. Open the integrated terminal (Terminal > New Terminal).
5. Install the required packages if you have not already:

   python -m pip install openai python-dotenv

6. Run the program from the terminal:

   python main.py

7. Enter your prompt when asked.