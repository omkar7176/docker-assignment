# Flask Interactive UI

Welcome to the Flask Interactive UI project! This is a simple web application built using Flask that demonstrates how to create a basic user interface with buttons and a footer.

## Features

- Interactive buttons that can be configured to perform actions.
- Responsive design with a sticky footer.
- Containerized using Docker for easy deployment.

## Prerequisites

- Python 3.x
- pip (Python package installer)
- Docker (for containerization)

## Project Structure
```bash
Your-local-foldername/
│
├── app.py                  # Main application file
├── Dockerfile              # Dockerfile for containerization
├── requirements.txt        # Python dependencies
├── .dockerignore           # Files to ignore in Docker build
├── static/                 # Static files (CSS, JS, images)
│   └── css/
│       └── style.css       # Stylesheet for the application
└── templates/              # HTML templates
    └── index.html          # Main HTML file
```
## Installation

### Clone the Repository

```bash
git clone https://github.com/omkar7176/docker-assignment.git
```

## Install Dependencies
1. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
2. Install the required Python packages:
   
```bash
pip install -r requirements.txt
```

## Run the Application

```bash
python app.py
```

## Access the Application
```bash
Open your web browser and navigate to http://127.0.0.1:5000/.
```

## License
This project is licensed under the <a>MIT License</a>. See the LICENSE file for more details.


## Acknowledgments
1. Flask: A micro web framework for Python.
2. Docker: A platform for developing, shipping, and running applications in containers.

### Customization

- **Repository Link**: Replace `https://github.com/yourusername/flask-interactive-ui.git` with the actual URL of your GitHub repository.
- **License**: If you have a specific license, make sure to provide the correct information or link to the license file.
- **Acknowledgments**: Feel free to add any additional acknowledgments or credits for libraries or resources you used.

### Saving the README

1. Create a file named `README.md` in the root directory of your project.
2. Copy and paste the content above into the `README.md` file.
3. Save the file.

This `README.md` provides a comprehensive overview of your project, making it easier for others (or yourself in the future) to understand how to set up and run your application.



