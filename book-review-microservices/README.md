Book Review Microservices Application

This project demonstrates a simple microservices-based architecture using Flask, Docker, Ansible, and NGINX for load balancing.
Features

    Flask-based User microservice

    Docker containerization

    NGINX reverse proxy for load balancing

    Ansible playbook for automated deployment

    Git-based version control and updates

Architecture

    user-service/ (Flask microservice)

    nginx/ (NGINX config)

    ansible/deploy.yml (Ansible automation)

    docker-compose.yml (Multi-container setup)

Getting Started

    Clone the repository:
    git clone https://github.com/XBorg04/book-review-microservices.git

    Run the Ansible playbook:
    ansible-playbook ansible/deploy.yml -i localhost,

    Open in browser:
    http://localhost/user

License

MIT License
