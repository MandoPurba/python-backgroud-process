# Job Processing System

This is a job processing system built using Python and the FastAPI framework. It allows users to submit jobs, retrieve job status, and view job results. The system uses Redis for job queueing and PostgreSQL for job storage.

## Features

- Submit jobs with a title and description
- Retrieve job status by job ID
- View job results by job ID


## Project Structure

The project is organized into the following directories:

- `src`: Contains the source code for the job processing system.
- `tests`: Contains unit and integration tests for the job processing system.

## Getting Started


```text
job-processing-system/

├── src/
│   ├── domain/
│   │   ├── __init__.py
│   │   ├── entities/
│   │   │   ├── __init__.py
│   │   │   └── job.py
│   │   └── repositories/
│   │       ├── __init__.py
│   │       └── job_repository.py
│   ├── infrastructure/
│   │   ├── __init__.py
│   │   ├── database/
│   │   │   ├── __init__.py
│   │   │   └── postgres.py
│   │   └── queue/
│   │       ├── __init__.py
│   │       └── redis_queue.py
│   ├── application/
│   │   ├── __init__.py
│   │   ├── services/
│   │   │   ├── __init__.py
│   │   │   └── job_service.py
│   │   └── dtos/
│   │       ├── __init__.py
│   │       └── job_dto.py
│   ├── interfaces/
│   │   ├── __init__.py
│   │   ├── api/
│   │   │   ├── __init__.py
│   │   │   ├── routes/
│   │   │   │   ├── __init__.py
│   │   │   │   └── job_routes.py
│   │   │   └── server.py
│   │   └── worker/
│   │       ├── __init__.py
│   │       └── consumer.py
│   └── core/
│       ├── __init__.py
│       ├── config.py
│       └── exceptions.py
├── tests/
│   ├── __init__.py
│   ├── unit/
│   │   └── test_job_service.py
│   └── integration/
│       └── test_consumer.py
├── pyproject.toml
└── README.md
```