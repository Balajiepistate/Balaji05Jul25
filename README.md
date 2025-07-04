
# EpidentAI

EpidentAI is an AI-powered Dental Clinical Assistant developed by Epistate Health. This Flask-based web application provides features such as doctor and patient registration, AI-driven image analysis (planned), treatment plan generation, and communication tools.

## Deployment on Render

1. Create a new Web Service on [Render](https://dashboard.render.com/).
2. Connect your GitHub repo or upload this ZIP as a Git repository.
3. Make sure `render.yaml` and `requirements.txt` are in the root.
4. Render will automatically use `render.yaml` to build and run the app.

## Project Structure

- `app.py`: Main Flask app
- `templates/`: HTML pages
- `static/`: CSS and uploads
- `render.yaml`: Configuration for Render deployment
- `.renderignore`: Ignore rules for Render deployment
- `requirements.txt`: Python dependencies
