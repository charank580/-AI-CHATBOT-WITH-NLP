# -AI-CHATBOT-WITH-NLP

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: KEMIDI SRI CHARAN

*INTERN ID*: CT04DY1913

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

##In this task, we developed an AI Chatbot using Python and Natural Language Processing (NLP) to create an interactive system capable of understanding user queries and providing relevant responses. The chatbot uses a predefined knowledge base consisting of question-answer pairs, which allows it to respond to common questions such as greetings, its own name, or how to generate PDF reports in Python. To process the user input and knowledge base efficiently, we used the NLTK library for text preprocessing, including tokenization, lemmatization, and stopword removal, which ensures the chatbot focuses on the most meaningful parts of the text. Both user queries and knowledge base questions are then converted into numerical vectors using TF-IDF vectorization from scikit-learn, and cosine similarity is calculated to find the closest matching response. If the similarity score exceeds a defined threshold, the chatbot returns the corresponding answer; otherwise, it provides a polite fallback message indicating it cannot understand the query. The chatbot runs as a terminal-based interactive program, continuously accepting input from the user and responding in real time until the user types “bye” or “exit.” This setup allows users to engage in a conversation with the bot and demonstrates the integration of NLP techniques, vectorization, and similarity-based retrieval in a simple AI application. The output of the project is a fully functional chatbot that can answer questions intelligently, such as replying “Hello! How can I help you today?” to greetings or providing guidance on generating PDF reports using Python. The main libraries used in the implementation are NLTK for text preprocessing, scikit-learn for vectorization and similarity computation, re for text cleaning, and random to select fallback responses when needed. This project illustrates a practical approach to building a retrieval-based chatbot using Python and demonstrates how natural language understanding, preprocessing, and vector-based matching can be combined to create an intelligent interactive system. Overall, this task successfully shows the complete procedure from preprocessing input, comparing it with a knowledge base, selecting the best response, and generating a working chatbot that can be tested in the terminal, making it a comprehensive example of applying NLP in real-world applications.
