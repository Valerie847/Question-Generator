Question Generator
**Project Overview**

Question Generator is a web application built using FastAPI, HTML, and CSS that allows users to generate questions based on a selected subject, topic, and number of questions. The application provides a simple and interactive interface where users can enter their preferences and receive automatically generated questions.

The goal of this project is to demonstrate web application development using Python, FastAPI, form handling, API integration, and dynamic content rendering.

**Steps / Approach**
1. Back-end Development
A FastAPI application was created to handle user requests and serve web pages.

2. Front-end Development
An HTML form was designed to collect:
Subject
Topic
Number of Questions
CSS was used to style the application and improve the user experience.

3. Form Processing
When the user submits the form, FastAPI receives the data through a POST request and validates the inputs.

4. Question Generation
The application creates a prompt based on the user's selections and sends it to an external AI-powered question generation API.

5. Response Handling
The API response is processed and converted into a list of questions.

6. Result Display
Generated questions are dynamically inserted into the webpage and displayed to the user.

**Future Improvements**
Support multiple AI providers.
Export generated questions to PDF.
Add question difficulty levels.
Improve error handling and validation.
Store generated questions in a database.
Add user authentication and saved question history.
Improve mobile responsiveness and user interface design.

Author
Valerie Enyonam