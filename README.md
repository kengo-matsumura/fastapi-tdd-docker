# Test-Driven Development with FastAPI and Docker

![Continuous Integration and Delivery](https://github.com/kengo-matsumura/fastapi-tdd-docker/workflows/Continuous%20Integration%20and%20Delivery/badge.svg?branch=main)

This project is based off the course [Test-Driven Development with FastAPI and Docker](https://testdriven.io/courses/tdd-fastapi/).

It focuses on test-driven development and the final product is a text summarisation service that is built using Python and the [FastAPI](https://fastapi.tiangolo.com/) framework. The service is exposed via a RESTful API that is deployed to Heroku with Docker.

The text summarisation component is integrated by using the [Newspaper3k](https://newspaper.readthedocs.io/en/latest/) library, which combines web scraping and summarisation (keywords) via the parse() and nlp() methods.