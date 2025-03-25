c:\Users\roman\UTProjects\Kelulusan\kelulusan-jobs\
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