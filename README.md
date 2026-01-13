QuizApplication
------------------------------------------------------------------------
A Quiz Application built with FastAPI, PostgreSQL, and SQLAlchemy, allowing you to create questions with multiple choices and store them in a relational database.
-----------------------------------------------------------------------
Technologies Used
- FastAPI → Modern, high-performance web framework for building APIs.

- SQLAlchemy → ORM for database modeling and queries.

- PostgreSQL → Relational database management system.

- pgAdmin4 → GUI tool for managing PostgreSQL databases.

----------------------------------------------------------------------
Project Structure
- database.py → Database connection setup and declarative base.

- models.py → Table definitions (questions and choices).

- main.py → FastAPI endpoints for creating questions and choices.

- init_db.py → Script to initialize tables in the database.

----------------------------------------------------------------------
Features
- Create questions with multiple choices.

- Mark correct answers for each question.

- Store and manage quiz data in PostgreSQL.

- Access and test endpoints via FastAPI’s interactive docs.
