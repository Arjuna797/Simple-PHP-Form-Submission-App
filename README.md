# Simple-PHP-Form-Submission-App
This project showcases how to process user input — such as name, email, and message — securely without a database or external dependencies. It’s perfect for beginners learning PHP form submission and Docker containerization
| Category             | Technology / Tool              | Purpose                               |
| -------------------- | ------------------------------ | ------------------------------------- |
| **Language**         | PHP 8.2                        | Backend scripting and form processing |
| **Web Server**       | Apache (via `php:8.2-apache`)  | Serves the PHP application            |
| **Containerization** | Docker, Docker Compose         | Isolated and portable environment     |
| **Frontend**         | HTML5, CSS3                    | Form UI and styling                   |
| **Runtime Option**   | PHP Built-in Server (`php -S`) | Local development without Docker      |


## Dependency Installation on Ubuntu

### System-Level Packages
Ensure Python 3 and pip are installed on your Ubuntu system. If not, install them using the following commands:

```bash
sudo apt update
sudo apt install python3 python3-pip python3-venv
```

### Setting Up a Virtual Environment
It is recommended to use a virtual environment to manage project dependencies.

1. Create a virtual environment in the project directory:
   ```bash
   python3 -m venv venv
   ```

2. Activate the virtual environment:
   ```bash
   source venv/bin/activate
   ```

### Installing Python Dependencies
Install the required Python packages using pip. The dependencies are listed in `requirements.txt`.

```bash
pip install -r requirements.txt
```

This will install:
- Flask==2.3.3

## Project Execution

### On Windows
1. Ensure Python 3.8+ is installed.
2. Navigate to the project directory.
3. Create and activate a virtual environment (similar to Ubuntu steps, but use `venv\Scripts\activate` on Windows).
4. Install dependencies: `pip install -r requirements.txt`
5. Run the application:
   ```bash
   python app.py
   ```
6. Open your browser and go to `http://127.0.0.1:5000/`

### On Ubuntu
1. Ensure Python 3.8+ and pip are installed (see Dependency Installation section).
2. Navigate to the project directory.
3. Activate the virtual environment:
   ```bash
   source venv/bin/activate
   ```
4. Run the application:
   ```bash
   python app.py
   ```
5. Open your browser and go to `http://127.0.0.1:5000/`


```bash
# On Ubuntu / Linux
docker-compose up -d

# On Windows
docker compose up -d
