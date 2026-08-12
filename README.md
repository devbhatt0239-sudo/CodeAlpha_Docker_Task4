CodeAlpha Docker Task 4
Project
Simple Nginx Docker Container serving a custom HTML page.

Tech Stack
Docker
Nginx
HTML
Build
docker build -t codealpha-task4 .

Run
docker run -d -p 8080:80 --name codealpha-container codealpha-task4

Access
http://localhost:8080
