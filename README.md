# Flask API Template
Easily get started with Flask by using this template. Put your API endpoints in `routes.py` and your Frontend code in the `frontend` folder to get started!

## Directory Structure
```sh
flask-api-template/
├─ .gitignore                    # Specifies files/directories to exclude from Git tracking
├─ backend/
│  ├─ .venv/                     # Python virtual environment for isolated dependencies
│  ├─ app/
│  │  ├─ data/
│  │  │  ├─ database_service.py  # Database connection and CRUD operations
│  │  │  └─ __init__.py          # Makes data directory a package
│  │  ├─ health/
│  │  │  └─ health_service.py    # Health check endpoints and service status
│  │  ├─ routes.py               # API endpoint definitions and request handlers
│  │  └─ __init__.py             # Flask app initialization and configuration
│  ├─ app.py                     # Main entry point for the Flask application
│  ├─ requirements.txt           # Python package dependencies
│  └─ tests/
│     ├─ conftest.py             # Pytest fixtures and test configuration
│     └─ __init__.py             # Makes tests directory a package
├─ frontend/
│  └─ README.md                  # Frontend documentation
└─ pyproject.toml                # Project metadata and build configuration
```
## How to Run Code Locally
1. Clone repo
```sh
https://github.com/michaelslice/flask-api-template.git
```
2. Go to repo, and to backend directory
```sh
cd flask-api-template/backend
```
3. Create virtual environment
```sh
python -m venv .venv
```
4. Start environment
```sh
.venv\Scripts\activate
```
5. Download packages
```sh
pip -r requirements.txt
```
6. Start the API!
```sh
python app.py
```

## Relevant Resources
- [Flask Documentation](https://flask.palletsprojects.com/en/stable/tutorial/)
