# fastapi-inventory-app

# FastAPI Inventory API

An inventory management API built with Python, utilizing a local SQLite3 database for persistence, Pydantic for data validation, and FastAPI for testing the backend routes.

## Tech Stack
* **Framework:** FastAPI
* **Data Validation:** Pydantic (v2)
* **Database:** SQLite3
* **Server:** Uvicorn

## Local Development (GitHub Codespaces)
The development environment is entirely containerized using Docker and VS Code Dev Containers. 

To run the application inside your Codespace terminal:
'''bash
uvicorn src.main:app --reload
'''
