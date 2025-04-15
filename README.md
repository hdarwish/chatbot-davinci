# Flask OpenAI Chatbot

A Flask-based web application that integrates with OpenAI's API to provide an interactive chatbot experience.

## ⚠️ Important Note
This project requires you to use your own OpenAI API key, which may incur costs based on your usage. For detailed pricing information, please visit [OpenAI's API pricing page](https://openai.com/pricing).

## Project Structure
```
.
├── app.py                 # Main application entry point
├── website/
│   ├── __init__.py       # Website package initialization
│   ├── routes.py         # Route handlers and API endpoints
│   ├── models.py         # Data models
│   ├── templates/        # HTML templates
│   └── static/           # Static files (CSS, JS, images)
```

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd chatbot-openai-flask
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up your OpenAI API key**
   - Create a `.env` file in the project root
   - Add your OpenAI API key:
     ```
     OPENAI_API_KEY=your_api_key_here
     ```

5. **Run the application**
   ```bash
   flask run --host=0.0.0.0
   ```

6. **Access the application**
   - Open your web browser and navigate to `http://localhost:5000`

## Features
- Interactive chat interface
- Real-time responses using OpenAI's API
- Chat history tracking
- Clean and responsive UI

## Dependencies
- Flask
- OpenAI
- python-dotenv

## Security Note
Never commit your `.env` file or expose your API key in the code. The `.env` file should be listed in your `.gitignore`.

## Contributing
Feel free to submit issues and enhancement requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details. 