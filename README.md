# Python Pollster Project with Django

Welcome to the "Python Pollster Project with Django"! This project is designed to provide a comprehensive polling platform using Django, allowing users to create, participate in, and analyze polls. Dive into the installation instructions below to get started with the project.

## Installation

Follow these steps to set up and run the Python Pollster Project with Django locally on your machine:

### Prerequisites

Before you begin, ensure that you have the following software installed on your machine:

- [Python](https://www.python.org/downloads/): The project is built using Python.
- [Git](https://git-scm.com/): Version control system to clone the repository.

### Clone the Repository

1. Open your terminal or command prompt.

2. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/Ammar-h22/python-django-pollster-project.git
    ```

### Navigate to the Project Directory

1. Change into the project directory:

    ```bash
    cd python-pollster
    ```

### Set Up a Virtual Environment (Optional but recommended)

1. Create a virtual environment to isolate project dependencies:

    ```bash
    python -m venv venv
    ```

2. Activate the virtual environment:

    - On Windows:

        ```bash
        .\venv\Scripts\activate
        ```

    - On macOS/Linux:

        ```bash
        source venv/bin/activate
        ```

### Install Django and Dependencies

1. Install Django and other required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

### Run the Application

1. Apply migrations:

    ```bash
    python manage.py migrate
    ```

2. Start the Django development server:

    ```bash
    python manage.py runserver
    ```

3. Open your web browser and go to [http://localhost:8000](http://localhost:8000) to access the Python Pollster Project.

Happy Coding!
