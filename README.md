# Locust Load Test

Load testing scripts using [Locust](https://locust.io/) for server performance testing.

## Project Structure

```
.
├── gathering-server-script/   # Load test scripts for Gathering server
├── trip-server-script/        # Load test scripts for Trip server
└── requirements.txt
```

## Prerequisites

- Python 3.x

## Installation

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Usage

```bash
locust -f gathering-server-script/locust.py
locust -f trip-server-script/locust.py
```

Then open `http://localhost:8089` in your browser to configure and start the test.
