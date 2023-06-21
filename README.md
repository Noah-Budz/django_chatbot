# AI Chatbot

This is an AI-powered chatbot web application built with Django and integrated with the OpenAI GPT-3.5 Turbo model. The chatbot allows users to have interactive conversations with the AI model by sending messages through a simple web interface.

## Features

- User registration and authentication
- Real-time chat interface
- Integration with OpenAI GPT-3.5 Turbo model for generating AI responses

## Installation

1. Clone the repository:

git clone https://github.com/your-username/ai-chatbot.git

2. Change to the project directory:

cd ai-chatbot

3. Create a virtual environment:

python3 -m venv venv

4. Activate the virtual environment:

- For macOS/Linux:

  ```
  source venv/bin/activate
  ```

- For Windows:

  ```
  venv\Scripts\activate
  ```

5. Install the dependencies:

pip install -r requirements.txt

6. Set up the database:

python manage.py migrate

7. Create a superuser (admin):

python manage.py createsuperuser

8. Start the development server:

python manage.py runserver

9. Open your web browser and visit `http://localhost:8000` to access the chatbot application.

## Usage

- Register a new user account or log in with an existing account.
- Enter your message in the input field and press Enter or click the Send button.
- The AI chatbot will generate a response based on your message and display it in the chat interface.
- Continue the conversation by entering additional messages.

## Contributing

Contributions to the AI Chatbot project are welcome! If you find any issues or would like to suggest enhancements, please create a new issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.