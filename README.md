This project consists of Python code within Jupyter Notebooks to implement an AI chatbot using TensorFlow and Keras. The chatbot is designed to understand and respond to various user inputs based on predefined intents. It loads conversation data from a JSON file and processes it to create a chatbot model to then respond to user inputs with predefined responses based on patterns and intents.

Key Components:
*Library Imports:
Importing essential libraries, including NumPy, Pandas, TensorFlow, Keras, and NLTK.
*Loading Conversation Data:
The project uses a JSON file ("chat.json") to define intents. Each intent includes a tag, input patterns, and responses.

*Data Preprocessing:
Extracting patterns and tags from the JSON data and storing them in lists.
Converting patterns to lowercase and removing punctuation.
Tokenizing and padding input data.

*Model Creation:
Defining a deep learning model with layers like Embedding, LSTM, Flatten, and Dense for classification.
Compiling the model with the categorical cross-entropy loss and the Adam optimizer.
Training the model with the processed data for 350 epochs.

*Chatbot Interaction:
Setting up a loop for the chatbot to interact with the user.
Taking user input and processing it.
Using the trained model to predict the appropriate response based on the user's input and the predefined intents.
Responding with a randomly selected response from the intent's responses.

*Loop Termination:
The chatbot continues to interact with the user until a "goodbye" intent is detected, at which point the loop breaks, ending the conversation.

# SARSA How to run
Download the python notebook file
Go on jupyter, upload and open the file
run all cells
Talk away!
