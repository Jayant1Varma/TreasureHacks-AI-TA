# TreasureHack

## Setting up
### Frontend
1. Install [Node.js](https://nodejs.org/en/download/).
2. Navigate to the FrontEnd folder and run `npm install` to install all the dependencies.
3. Run `npm start` to start the frontend server. This creates a `dist` folder which contains the required files.

### Backend
1. Install [Python](https://www.python.org/downloads/).
2. Create a virtual environment using `python -m venv venv`.
3. Activate the virtual environment using `venv/Scripts/activate`.
4. Install the dependencies using `pip install -r requirements.txt`.
5. Set environment variable for `OPENAI_API_KEY` to your OpenAI API key.
6. Run `flask --app main run --debug` to start the backend server in development mode.
