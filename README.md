# Hello API

A simple Flask application that returns a JSON message.

## Requirements

- Python 3.12.1
- Flask (installed via pip)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/endxff/hello-api-flask.git
   cd hello-api-flask
   ```

2. Install dependencies:
   
    ```bash
   pip install flask
   ```
    
## Usage

1. Run the Flask app:
   ```bash
   python app.py
   ```
2. Open your browser and navigate to:
   ```bash
   http://127.0.0.1:5000/hello
   ```
## API Endpoint

GET /hello
Returns a JSON response:
   ```bash
   {
   "message": "Hello, World!"
   }
   ```
