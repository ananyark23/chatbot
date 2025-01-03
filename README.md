
# Chatbot using NLP

## Overview
This project implements a chatbot using Natural Language Processing (NLP) techniques. The chatbot is designed to understand user intents and provide appropriate responses based on predefined patterns and responses. It utilizes the `nltk` library for natural language processing, `scikit-learn` for machine learning, and `streamlit` for creating an interactive web interface.

---

## Features
- Understands various user intents such as greetings, farewells, gratitude, and more.
- Provides relevant responses based on user input.
- Maintains a conversation history that can be viewed by the user.
- Built using Python and leverages popular libraries for NLP and machine learning.
------
output
![Screenshot 2024-12-30 211539](https://github.com/user-attachments/assets/a03efb08-a417-4de5-b1a1-410b0cc92e76)

![Screenshot 2024-12-30 211610](https://github.com/user-attachments/assets/f653be8c-d473-44d6-9fad-bfe8dc4abf4d)

![Screenshot 2024-12-30 205209](https://github.com/user-attachments/assets/26aa3304-1266-4fde-8847-244ffb8c33aa)
  

![Screenshot 2024-12-30 205944](https://github.com/user-attachments/assets/61d64648-d92c-4e83-a1b9-0f199106431c)

![Screenshot 2024-12-30 210110](https://github.com/user-attachments/assets/228a41d3-1c54-4028-b0fd-ab66c01f20a6)

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

Once the application is running, you can interact with the chatbot through the web interface. Type your message in the input box and press Enter to see the chatbot's response.

---

## Intents Data
The chatbot's behavior is defined by the `intents.json` file, which contains various tags, patterns, and responses. You can modify this file to add new intents or change existing ones.

---

## Conversation History
The chatbot saves the conversation history in a CSV file (`chat_log.csv`). You can view past interactions by selecting the "Conversation History" option in the sidebar.


---

## Acknowledgments
- **NLTK** for natural language processing.
- **Scikit-learn** for machine learning algorithms.
- **Streamlit** for building the web interface.

---



Replace `<repository-url>` and `<repository-directory>` with the actual URL of your repository and the name of the directory where the project is located. Adjust any sections as necessary to better fit your project's specifics.
