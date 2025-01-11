# FastAPI Demo Project

Welcome to the **FastAPI Demo Project**! This repository provides a beginner-friendly implementation of a FastAPI application to help new developers learn the basics of FastAPI.

## Features
- **FastAPI Basics**: Learn to create endpoints and manage requests.
- **Virtual Environment Setup**: Keep your project dependencies isolated.
- **Beginner-Friendly Code**: Simple and clear structure.

## Prerequisites
- Python 3.8 or higher
- Git

## Getting Started
Follow these steps to set up and run the project locally.

### 1. Clone the Repository
```bash
git clone https://github.com/harimoradiya/FastAPI-Demo.git
cd FastAPI-Demo
```

### 2. Create and Activate a Virtual Environment
#### On Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

#### On macOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the FastAPI Application
Start the FastAPI server:
```bash
uvicorn main:app --reload
```

- The application will be accessible at `http://127.0.0.1:8000`.
- Open `http://127.0.0.1:8000/docs` to explore the Swagger UI documentation.

## Project Structure
```
FastAPI-Demo/
├── main.py            # Main FastAPI application file
├── requirements.txt   # List of dependencies
├── .gitignore         # Ignored files for Git
├── README.md          # Project documentation (this file)
└── venv/              # Virtual environment (not included in Git)
```

## Example Endpoint
Here is an example of an endpoint you can try:

- **GET /**: Returns a welcome message.

#### Example Request:
```bash
curl -X 'GET' \
  'http://127.0.0.1:8000/' \
  -H 'accept: application/json'
```

#### Example Response:
```json
{
  "message": "Restaurant Management System"
}
```

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
- [FastAPI Documentation](https://fastapi.tiangolo.com/)
- [Uvicorn Documentation](https://www.uvicorn.org/)

---

Happy coding!
