# Chat with Files: QnA Chatbot for PDFs

[![GitHub stars](https://img.shields.io/github/stars/HemantModi11/ChatwithDocs)](https://github.com/HemantModi11/ChatwithDocs/stargazers)
![GitHub](https://img.shields.io/github/license/HemantModi11/ChatwithDocs)

### Introduction
Chat with Files is an AI-powered QnA chatbot built on the Llama 70b model, designed to extract information and answer questions from multiple PDF documents. This application simplifies information retrieval from documents, enabling streamlined communication with large volumes of textual data.

### Demo
Visit the live application: [Chat with Files](https://chatwithfiles.streamlit.app/)

### Features
- Perform QnA on multiple PDFs simultaneously.
- Intuitive user interface for easy interaction.
- Extracts information swiftly from uploaded documents.
- Provides accurate responses to inquiries based on PDF content.

### Usage
To use this project locally:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/HemantModi11/ChatwithDocs.git
    cd ChatwithDocs
    ```

2. **Create a virtual environment:**
    ```bash
    python3 -m venv venv
    ```

3. **Activate the virtual environment:**
    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS and Linux:
      ```bash
      source venv/bin/activate
      ```

4. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

5. **Run the application:**
    ```bash
    streamlit run app.py
    ```

6. **Access the application:**
    - Open your web browser and go to [http://localhost:8501](http://localhost:8501) to interact with the chatbot.
    - Upload PDFs and wait for a few moments for document processing.
    - The QnA section will become available once the PDFs have been processed.

**NOTE**: Please assign your replicate token key in the .env file, you can get your key from [Replicate](https://replicate.com/) for free.

### Contributing
Contributions are welcome! Please create a pull request with proposed changes.

### Issues
Found a bug or have suggestions? Please open an issue [here](https://github.com/HemantModi11/ChatwithDocs/issues).

### License
This project is licensed under the [MIT License](LICENSE).

### Author
[Hemant Modi](https://github.com/HemantModi11)

---
