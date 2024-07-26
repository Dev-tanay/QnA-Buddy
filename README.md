# QnA Buddy
Welcome to **QnA Buddy**, a powerful tool that allows you to ask questions and receive answers using the Gemini LLM. You can access the webapp [here](https://qna-buddy.onrender.com/).

## Getting Started

### Prerequisites
- Python 3.11
- Streamlit

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/qna-buddy.git
    cd qna_buddy
    ```
2. Create and activate a Python virtual environment:
    - **Windows**:
        ```powershell
        python -m venv venv
        .\venv\Scripts\activate
        ```
    - **Linux**:
        ```bash
        python3 -m venv venv
        source venv/bin/activate
        ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Set the environment variable `GOOGLE_API_KEY` in the .env file present in your root directory with your own Google API key.

## Usage
1. Open the webapp in your browser:
    ```bash
    streamlit run app.py
    ```
2. Enter your question in the text box and click on "Ask the question" to get a response from the Gemini LLM.

## Project Structure
- `app.py`: The main file that runs the Streamlit webapp.
- `requirements.txt`: List of Python libraries required to run the app.

## Contributing
We welcome contributions! If you have suggestions or improvements, please create a pull request or open an issue.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [Streamlit](https://www.streamlit.io/) for providing an amazing platform to build the webapp.
- All contributors and users for their valuable feedback and support.
