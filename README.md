# AirBnB Clone - RESTful API

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies](#technologies)
- [Requirements](#requirements)
  - [General](#general)
- [Directory Structure](#directory-structure)
- [Tasks](#tasks)
- [C Scripts](#c-scripts)
- [Author](#author)

## Project Overview
This project is part of the SE Foundations curriculum and involves building a RESTful API for the AirBnB clone project. The API handles various HTTP methods to perform CRUD operations on different objects such as users, states, cities, amenities, places, and reviews.

## Technologies
- Python 3.4.3
- Flask 2.0.2
- SQLAlchemy
- Unittest
- Ubuntu 20.04 LTS

## Requirements

### General
- All Python files must be executable and follow PEP 8 style guidelines.
- Unit tests must be included, using the `unittest` module.
- A `README.md` file at the root of the project folder is mandatory.
- The codebase will be tested using `python3 -m unittest discover tests`.

## Directory Structure
```
AirBnB_clone_v3/
├── api/
│   ├── __init__.py
│   ├── v1/
│   │   ├── __init__.py
│   │   ├── app.py
│   │   └── views/
│   │       ├── __init__.py
│   │       ├── index.py
│   │       └── states.py
├── models/
│   ├── __init__.py
│   ├── base_model.py
│   ├── engine/
│   │   ├── db_storage.py
│   │   ├── file_storage.py
├── tests/
│   ├── __init__.py
│   ├── test_models/
│   │   └── test_engine/
│   │       ├── test_db_storage.py
│   │       ├── test_file_storage.py
│   ├── test_api/
│       └── test_v1/
│           └── test_views/
└── README.md
```

## Tasks

| Task Number | File Name                              | Description                                                                      |
|-------------|----------------------------------------|----------------------------------------------------------------------------------|
| 0           | [README.md](README.md)                 | Update the README.md with project information and contributions.                 |
| 1           | [test_get_count.py](test_get_count.py) | Add tests for the `get()` and `count()` methods in `DBStorage` and `FileStorage`. |
| 2           | [index.py](api/v1/views/index.py)      | Create an endpoint to return the API status.                                      |
| 3           | [index.py](api/v1/views/index.py)      | Create an endpoint to return the number of objects by type.                       |
| 4           | [app.py](api/v1/app.py)                | Implement a 404 error handler returning JSON response.                            |
| 5           | [states.py](api/v1/views/states.py)    | Create views for State objects handling all RESTful actions.                      |

## C Scripts
(No C scripts for this project)

## Author :black_nib:
* **Ifeanyi I Ekezie** - [iiekezie](https://github.com/iiekezie)