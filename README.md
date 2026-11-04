# DevOps Capstone Project

[![Build Status](https://github.com/plash911/devops-capstone-project/actions/workflows/ci-build.yaml/badge.svg)](https://github.com/plash911/devops-capstone-project/actions)

This repository contains the starter code for the project in [**IBM-CD0285EN-SkillsNetwork DevOps Capstone Project**](https://www.coursera.org/learn/devops-capstone-project) which is part of the [**IBM DevOps and Software Engineering Professional Certificate**](https://www.coursera.org/professional-certificates/devops-and-software-engineering)

## Usage

This template should be used to start your paths into the DevOps Capstone project. It contains all of the code that you will need to get started.

Do **NOT** fork this code! Instead, use the green **Use this template** button from the GitHub UI to create a new repository under your own account from this template.

## Accounts Microservice

The Accounts microservice manages customer accounts and supports full CRUD operations:

| Endpoint | Method | Description |
| --- | --- | --- |
| `/` | `GET` | Returns service metadata and health status |
| `/health` | `GET` | Returns HTTP 200 OK health check |
| `/accounts` | `POST` | Creates a new customer account |
| `/accounts` | `GET` | Lists all customer accounts |
| `/accounts/<id>` | `GET` | Reads a single customer account by ID |
| `/accounts/<id>` | `PUT` | Updates an existing customer account by ID |
| `/accounts/<id>` | `DELETE` | Deletes a customer account by ID |

## Running Tests Locally

```bash
nosetests
flake8 service tests
```
