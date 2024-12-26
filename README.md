
# Universe Chatbot using NLP

## Overview
This project implements a chatbot using Natural Language Processing (NLP) techniques to explore various cosmic phenomena. The chatbot is designed to understand user intents related to the universe, including topics like planets, stars, galaxies, black holes, the Big Bang, space exploration, exoplanets, and more. It provides appropriate responses based on predefined patterns and responses. The chatbot is built using the nltk library for NLP, scikit-learn for machine learning, and streamlit for creating an interactive web interface.

---

## Features
- Understands user intents related to the universe such as greetings, planets, stars, black holes, galaxies, Big Bang, space exploration, exoplanets, cosmic events, and more.
- Provides relevant responses based on user input with detailed explanations of cosmic phenomena.
- Maintains a conversation history that can be viewed by the user.
- Built using Python and leverages popular libraries for NLP and machine learning.
---

## Technologies Used
- **Python**
- **NLTK**
- **Scikit-learn**
- **Streamlit**
- **JSON** for intents data

---

## Installation

### 1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Required Packages
```bash
pip install -r requirements.txt
```

### 4. Download NLTK Data
```python
import nltk
nltk.download('punkt')
```

---

## Usage
To run the chatbot application, execute the following command:
```bash
streamlit run app.py
```

Once the application is running, you can interact with the chatbot through the web interface. Type your message in the input box and press Enter to see the chatbot's response. You can inquire about topics such as planets, stars, galaxies, black holes, Big Bang, space exploration, and more.

---

## Intents Data
The chatbot’s behavior is defined by the intents.json file, which contains various tags, patterns, and responses related to the universe and cosmic phenomena. You can modify this file to add new intents or change existing ones. The intents include topics like:

- Planets (e.g., "What are the planets in our solar system?")
- Stars (e.g., "Tell me about stars")
- Galaxies (e.g., "What is a galaxy?")
- Black Holes (e.g., "What is a black hole?")
- Big Bang (e.g., "Explain the Big Bang theory")
- Space Exploration (e.g., "Tell me about space exploration")
- Exoplanets (e.g., "What are exoplanets?")
- Cosmic Events (e.g., "Tell me about supernovae")
- Universe (e.g., "What is the universe?")
---

## Conversation History
The chatbot saves the conversation history in a CSV file (`chat_log.csv`). You can view past interactions by selecting the "Conversation History" option in the sidebar.

---

## Contributing
Contributions to this project are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- **NLTK** for natural language processing.
- **Scikit-learn** for machine learning algorithms.
- **Streamlit** for building the web interface.

---

Replace `<repository-url>` and `<repository-directory>` with the actual URL of your repository and the name of the directory where the project is located. Adjust any sections as necessary to better fit your project's specifics.
