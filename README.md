# Pinecone-Athena
Let's use Pinecone to make a realistic Personal Assistant with INFINITE MEMORY

Code by https://github.com/daveshap/

## Windows Installation

1. Install Git
2. Install Python 3.10.6, Make sure you add it to PATH
3. Run git clone: "git clone https://github.com/libraryofcelsus/Pinecone-Athena/"
4. Create a virtual environment: "python3 -m venv env"
5. Activate the environment: ".\env\Scripts\activate"
6. Install the required packages: "pip install openai numpy pinecone-client"
7. Copy your OpenAI api key to key_openai and your Pinecone api key to key_pinecone
8. Create a Index on Pinecone titled: "athena" with 1536 dimensions and cosine as the metric. I usually do a P1 instance.
9. Run chat.py with Python 3.10.6
10. Teach Athena by asking leading questions, remember this is nothing but a text completion engine with a script on top of it. Keep this in mind when having your initial conversations, as these will be Athena's first memories.
11. Please don't date the Ai.

## Changing Personality

To edit the personality, change the two prompts in the prompt_response.txt file.
Making the prompt to long or detailed may lead to a breakdown of conversation later.
To help avoid this, I suggest telling Athena to research conversation structure and flow. Then tell Athena to implement what she learned about conversations in every future interaction. If you plan on teaching it specific emotions, have Athena define them with leading questions before teaching it conversation structure.
After teaching Athena converation structure, next is to teach it when to use emotions. Have it define when an emotion should be shown with leading questions, have it provide allegories to any situation it gives to help increase its understanding.
If Athena is ever repeating itself to much, tell it to stop. Non repetition training is highly important in the initial conversations.
