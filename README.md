# Simple-PHP-Form-Submission-App
This project showcases how to process user input — such as name, email, and message — securely without a database or external dependencies. It’s perfect for beginners learning PHP form submission and Docker containerization
| Category             | Technology / Tool              | Purpose                               |
| -------------------- | ------------------------------ | ------------------------------------- |
| **Language**         | PHP 8.2                        | Backend scripting and form processing |
| **Web Server**       | Apache (via `php:8.2-apache`)  | Serves the PHP application            |
| **Containerization** | Docker, Docker Compose         | Isolated and portable environment     |
| **Frontend**         | HTML5, CSS3                    | Form UI and styling                   |
| **Runtime Option**   | PHP Built-in Server (`php -S`) | Local development without Docker      |
```bash
# On Ubuntu / Linux
docker-compose up -d

# On Windows
docker compose up -d
