# WebSocket Example
This is an example of a chat application using WebSockets. It is a simple chat application that allows users to send messages to each other in real-time. The application uses FastAPI for the backend and HTML/pure JavaScript for the front end.

## Project Structure
The project is structured as follows:
```
.
├── README.md          # This file
├── app
│   └── main.py        # FastAPI application (backend)
├── index.html         # HTML file (frontend)
└── requirements.txt   # Python dependencies
```

## Setting Up the Project
To set up the project, follow these steps:

1. Clone the repository:
 ```bash
   git clone https://github.com/marcioreisjr/WebSocket.git
   cd WebSocket
 ```
2. Activate a virtual environment:
 ```bash
   python3 -m .venv .venv
   source .venv/bin/activate
 ```
3. Install the dependencies:
 ```bash
   pip install -r requirements.txt
 ```

## Running the Project
1. Open a terminal and navigate to the project directory.
2. Run the FastAPI application to start the WebSocket server:
 ```bash
   uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
 ```
3. Open your browser and navigate to `http://localhost:8000` to access the chat application.
4. Open multiple browser tabs or windows to the same URL to simulate various users chatting with each other.
