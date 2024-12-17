# Homework 10
#### Event Manager Company: Software QA Analyst/Developer

## Overview

This repository contains the source code for the Event Manager project, a web application developed using FastAPI, PostgreSQL, and Docker to streamline event management. The application includes key functionalities such as user authentication, role-based access control, and email notification capabilities.

This document outlines the project's progress, addresses both resolved and ongoing challenges, and reflects on the lessons learned throughout the development process.

## Github Links

**Closed Issues**:
1. [Issue#1](https://github.com/aGreekGeek/Homework10/issues/1)
2.
3. [Issue#3](https://github.com/aGreekGeek/Homework10/issues/3)
4. [Issue#4](https://github.com/aGreekGeek/Homework10/issues/4)
5.


**Dockerhub Image**


**Challenges**

Throughout this assignment, I faced several complex challenges, including schema validation errors, SMTP connection issues, and difficulties implementing role-based permissions. While I successfully addressed many of these problems—such as utilizing mock SMTP clients for testing and refining fixtures to improve schema validation—some challenges persisted. For example, despite creating robust test fixtures and configurations, intermittent issues with the UserRole enum type and table-related inconsistencies in PostgreSQL continued to occur, even after dropping and recreating the database.

Debugging these errors significantly enhanced my skills in database migrations using Alembic, service mocking, and developing clean, reusable test fixtures. Additionally, I gained a deeper understanding of the FastAPI ecosystem and learned the importance of maintaining a modular structure in key components like email_service and user_service.

Collaborative and Process-Oriented Insights
This project highlighted the critical role of version control and GitHub issue tracking in managing complex development workflows. I adopted a practice where each branch was dedicated to a single feature or bug fix and ensured thorough documentation of issues to streamline troubleshooting and track progress. However, handling merge conflicts and ensuring branch compatibility proved to be more challenging than expected. This experience underscored the importance of clear communication, descriptive commit messages, and incremental development.

Setting up Dockerized environments for PostgreSQL and FastAPI was another key takeaway from this project. This process taught me the value of containerization for managing dependencies and ensuring project reproducibility across different systems. While Docker simplified deployment, debugging containerized services introduced additional complexity, such as verifying inter-service communication within a docker-compose setup.

These challenges collectively contributed to a more structured, modular, and efficient approach to development, enhancing both my technical and collaborative skills.

All in all, I basically ended up giving up. 

