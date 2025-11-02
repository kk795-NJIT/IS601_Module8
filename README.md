# FastAPI Calculator Application# FastAPI Calculator - Module 8 Assignment# FastAPI Calculator - Module 8 Assignment# FastAPI Calculator - Module 8 Assignment# 📦 Project Setup



## Overview



A production-grade FastAPI-based calculator web application demonstrating professional software engineering practices including comprehensive test coverage (100%), structured logging, CI/CD automation, RESTful API design, and enterprise-level code quality standards.A comprehensive FastAPI-based calculator application with full test coverage, logging, and CI/CD integration.



## Table of Contents



- [Features](#features)## 🚀 Quick StartA comprehensive FastAPI-based calculator application with full test coverage, logging, and CI/CD integration.

- [Technology Stack](#technology-stack)

- [Getting Started](#getting-started)

- [API Documentation](#api-documentation)

- [Testing](#testing)### 1. Clone the Repository

- [Project Structure](#project-structure)

- [CI/CD Pipeline](#cicd-pipeline)```bash



## Featuresgit clone https://github.com/kk795-NJIT/IS601_Module8.gitA comprehensive FastAPI-based calculator application with full test coverage, logging, and CI/CD integration.A comprehensive FastAPI-based calculator application with full test coverage, logging, and CI/CD integration.---



### Core Functionalitycd IS601_Module8

- **Arithmetic Operations**: Add, subtract, multiply, and divide operations

- **Web Interface**: Interactive calculator UI at http://localhost:8000```

- **RESTful API**: Well-designed API endpoints with proper error handling

- **Input Validation**: Comprehensive validation of user inputs

- **Error Handling**: Graceful error handling for edge cases (e.g., division by zero)

### 2. Set Up Python Environment## 📋 Project Overview

### Quality Assurance

- **100% Code Coverage**: All code paths tested```bash

- **50 Comprehensive Tests**:

  - 35 Unit Testspython -m venv venv

  - 10 Integration Tests

  - 5 End-to-End Testssource venv/bin/activate  # macOS/Linux

- **Automated Testing**: GitHub Actions CI/CD pipeline

- **Code Quality**: Pylint and security scanning# orThis project demonstrates professional software engineering practices including:## 📋 Project Overview# 🧩 1. Install Homebrew (Mac Only)



### Logging & Monitoringvenv\Scripts\activate  # Windows

- **Structured Logging**: INFO, DEBUG, and ERROR level logging

- **Multiple Outputs**: Console and file-based logging (app.log)```- ✅ RESTful API design with FastAPI

- **Operation Tracking**: All operations logged with timestamps

- **Error Tracking**: Comprehensive error logging and diagnostics



## Technology Stack### 3. Install Dependencies- ✅ Unit, Integration, and End-to-End Testing (50+ tests with 100% coverage)



| Category | Technology | Version |```bash

|----------|-----------|---------|

| Framework | FastAPI | 0.115.4 |pip install -r requirements.txt- ✅ Comprehensive logging and monitoring

| Server | Uvicorn | 0.32.0 |

| Validation | Pydantic | 2.9.2 |```

| Templating | Jinja2 | 3.1.4 |

| Testing | Pytest | 8.3.3 |- ✅ Continuous Integration/Continuous Deployment (CI/CD) with GitHub ActionsThis project demonstrates professional software engineering practices including:> Skip this step if you're on Windows.

| Coverage | Coverage.py | 6.0.0 |

| E2E Testing | Playwright | 1.48.0 |### 4. Run the Application

| CI/CD | GitHub Actions | - |

| Language | Python | 3.10+ |```bash- ✅ Docker containerization

| Containerization | Docker | - |

python main.py

## Getting Started

```- ✅ Professional documentation- ✅ RESTful API design with FastAPI

### Prerequisites



- Python 3.10 or higher

- pip (Python package manager)Visit: **http://localhost:8000**

- Git



### Installation

## 🧪 Running Tests## 🎯 Assignment Requirements - ✅ COMPLETED- ✅ Unit, Integration, and End-to-End Testing (50+ tests with 100% coverage)Homebrew is a package manager for macOS.  

1. **Clone the Repository**

   ```bash

   git clone https://github.com/kk795-NJIT/IS601_Module8.git

   cd IS601_Module8```bash

   ```

# All tests

2. **Create Virtual Environment**

   ```bashpytest tests/ -v --cov=app### Submission Completeness (50 Points)- ✅ Comprehensive logging and monitoringYou’ll use it to easily install Git, Python, Docker, etc.

   python -m venv venv

   ```



3. **Activate Virtual Environment**# Unit tests only

   ```bash

   # macOS/Linuxpytest tests/unit/ -v

   source venv/bin/activate

   #### ✅ GitHub Repository Link- ✅ Continuous Integration/Continuous Deployment (CI/CD) with GitHub Actions

   # Windows

   venv\Scripts\activate# Integration tests only

   ```

pytest tests/integration/ -v- **Repository**: https://github.com/kk795-NJIT/IS601_Module8.git

4. **Install Dependencies**

   ```bash

   pip install -r requirements.txt

   ```# E2E tests only- **Branch**: main- ✅ Docker containerization**Install Homebrew:**



5. **Run Application**pytest tests/e2e/ -v

   ```bash

   python main.py```- **Status**: Public and accessible

   ```



6. **Access Application**

   - Web Interface: http://localhost:8000## 📊 Project Status- ✅ Professional documentation

   - API Documentation: http://localhost:8000/docs

   - ReDoc Documentation: http://localhost:8000/redoc



## API Documentation- ✅ Unit Tests: 35 passing (100% coverage)#### ✅ Project Contents



### Endpoints- ✅ Integration Tests: 10 passing



#### Addition- ✅ E2E Tests: 5 passing- FastAPI application code with logging```bash

```http

POST /add- ✅ Total: 50/50 tests passing

Content-Type: application/json

- ✅ Code Coverage: 100% on operations module- Comprehensive test suite (unit, integration, E2E)

{

  "a": 10,- ✅ GitHub Actions: CI/CD pipeline operational

  "b": 5

}- requirements.txt with all dependencies## 🎯 Assignment Requirements - ✅ COMPLETED/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

```

**Response**: `{"result": 15}`## 📁 Project Structure



#### Subtraction```- GitHub Actions workflow for CI/CD

```http

POST /subtractIS601_Module8/

Content-Type: application/json

├── main.py                          # FastAPI application- Dockerfile for containerization```

{

  "a": 10,├── app/

  "b": 5

}│   └── operations/__init__.py        # Calculator operations (100% coverage)- Complete documentation

```

**Response**: `{"result": 5}`├── templates/



#### Multiplication│   └── index.html                   # Frontend UI### Submission Completeness (50 Points)

```http

POST /multiply├── tests/

Content-Type: application/json

│   ├── unit/### Functionality of Web Application and Tests (50 Points)

{

  "a": 10,│   │   └── test_calculator.py        # 35 unit tests

  "b": 5

}│   ├── integration/**Verify Homebrew:**

```

**Response**: `{"result": 50}`│   │   └── test_fastapi_calculator.py # 10 integration tests



#### Division│   ├── e2e/#### ✅ Web Application

```http

POST /divide│   │   └── test_e2e.py              # 5 E2E tests

Content-Type: application/json

│   └── conftest.py                  # Test configuration- **Framework**: FastAPI#### ✅ GitHub Repository Link

{

  "a": 10,├── .github/workflows/

  "b": 2

}│   └── test.yml                     # GitHub Actions workflow- **Port**: 8000

```

**Response**: `{"result": 5.0}`├── requirements.txt                 # Python dependencies



**Error Response (Division by Zero)**:├── pytest.ini                       # Pytest configuration- **Endpoints**: `/` (homepage), `/add`, `/subtract`, `/multiply`, `/divide`- **Repository**: https://github.com/kk795-NJIT/IS601_Module8.git```bash

```http

POST /divide├── Dockerfile                       # Docker configuration

Content-Type: application/json

└── README.md                        # This file- **Status**: Fully operational with error handling

{

  "a": 10,```

  "b": 0

}- **Operations**: All arithmetic operations function correctly- **Branch**: mainbrew --version

```

**Response**: ## 📱 API Endpoints

```json

{

  "error": "Cannot divide by zero!"

}### Addition

```

```bash#### ✅ Test Implementation & Results- **Status**: Public and accessible```

## Testing

curl -X POST "http://localhost:8000/add" \

### Running All Tests

```bash  -H "Content-Type: application/json" \- **Unit Tests**: 35 passing (100% code coverage)

pytest tests/ -v --cov=app --cov-report=html

```  -d '{"a": 10, "b": 5}'



### Running Specific Test Suites```- **Integration Tests**: 10 passing

```bash

# Unit Tests

pytest tests/unit/ -v

### Subtraction- **E2E Tests**: 5 passing

# Integration Tests

pytest tests/integration/ -v```bash



# End-to-End Testscurl -X POST "http://localhost:8000/subtract" \- **Total**: 50 passing tests#### ✅ Project ContentsIf you see a version number, you're good to go.

pytest tests/e2e/ -v

```  -H "Content-Type: application/json" \



### Coverage Report  -d '{"a": 10, "b": 5}'- **Coverage**: 100% on operations module

```bash

# Generate coverage report```

pytest tests/ --cov=app --cov-report=html

- **CI/CD**: GitHub Actions workflow successful- FastAPI application code with logging

# View in browser

open htmlcov/index.html  # macOS### Multiplication

# or

start htmlcov/index.html  # Windows```bash

```

curl -X POST "http://localhost:8000/multiply" \

### Test Results

  -H "Content-Type: application/json" \## 🚀 Quick Start- Comprehensive test suite (unit, integration, E2E)---

| Category | Tests | Status |

|----------|-------|--------|  -d '{"a": 10, "b": 5}'

| Unit Tests | 35 | ✅ All Passing |

| Integration Tests | 10 | ✅ All Passing |```

| E2E Tests | 5 | ✅ All Passing |

| **Total** | **50** | **✅ 100% Pass Rate** |



### Code Coverage### Division### 1. Clone the Repository- requirements.txt with all dependencies



``````bash

app/operations/__init__.py

  Lines: 27curl -X POST "http://localhost:8000/divide" \```bash

  Coverage: 100%

  Missed: 0  -H "Content-Type: application/json" \

```

  -d '{"a": 10, "b": 2}'git clone https://github.com/kk795-NJIT/IS601_Module8.git- GitHub Actions workflow for CI/CD# 🧩 2. Install and Configure Git

## Project Structure

```

```

IS601_Module8/cd IS601_Module8

├── main.py                              # FastAPI application entry point

├── app/## 🔗 Repository

│   └── operations/

│       └── __init__.py                  # Core arithmetic operations```- Dockerfile for containerization

├── templates/

│   └── index.html                       # Web UI template- **GitHub**: https://github.com/kk795-NJIT/IS601_Module8.git

├── tests/

│   ├── __init__.py- **Branch**: main

│   ├── conftest.py                      # Pytest configuration

│   ├── unit/- **Visibility**: Public

│   │   ├── __init__.py

│   │   └── test_calculator.py           # Unit tests (35 tests)### 2. Set Up Python Environment- Complete documentation## Install Git

│   ├── integration/

│   │   ├── __init__.py## ✅ Assignment Requirements Met

│   │   └── test_fastapi_calculator.py   # Integration tests (10 tests)

│   └── e2e/```bash

│       ├── __init__.py

│       └── test_e2e.py                  # E2E tests (5 tests)- ✅ FastAPI Calculator application

├── .github/

│   └── workflows/- ✅ Unit, integration, and E2E tests# Create virtual environment

│       └── test.yml                     # GitHub Actions workflow

├── requirements.txt                     # Python dependencies- ✅ Comprehensive logging

├── pytest.ini                           # Pytest configuration

├── Dockerfile                           # Docker configuration- ✅ GitHub Actions CI/CDpython -m venv venv

├── docker-compose.yml                   # Docker Compose configuration

├── LICENSE                              # MIT License- ✅ 100% code coverage

└── README.md                            # This file

```- ✅ All tests passing### Functionality of Web Application and Tests (50 Points)- **MacOS (using Homebrew)**



## CI/CD Pipeline



### GitHub Actions Workflow## 🎓 Learning Outcomes# Activate virtual environment



**File**: `.github/workflows/test.yml`



**Stages**:**CLO10**: Create, Consume and Test REST APIs using Python# On macOS/Linux:



1. **Test Job**- ✅ Created FastAPI REST API with 4 endpoints

   - Checkout code

   - Setup Python 3.10- ✅ Consumed APIs with integration testssource venv/bin/activate

   - Cache dependencies

   - Install requirements- ✅ Tested with 50 comprehensive tests

   - Run unit tests with coverage

   - Run integration tests# On Windows:#### ✅ Web Application```bash

   - Run E2E tests

   - Upload test results---

   - Upload coverage reports

venv\Scripts\activate

2. **Security Job**

   - Build Docker image**Status**: Production Ready ✅

   - Run Trivy vulnerability scanning

   - Validate against security policies```- **Framework**: FastAPIbrew install git



3. **Code Quality Job**

   - Run Pylint checks

   - Validate code standards### 3. Install Dependencies- **Port**: 8000```



### Triggers```bash



- Push to main branchpip install -r requirements.txt- **Endpoints**: `/` (homepage), `/add`, `/subtract`, `/multiply`, `/divide`

- Pull requests to main branch

```

### Status

- **Status**: Fully operational with error handling- **Windows**

- **Current Status**: ✅ Passing

- **Test Results**: All 50 tests passing### 4. Run the Application

- **Coverage**: 100% on operations module

- **Security**: No critical vulnerabilities```bash- **Operations**: All arithmetic operations function correctly



## Docker Supportpython main.py



### Build Image```Download and install [Git for Windows](https://git-scm.com/download/win).  

```bash

docker build -t fastapi-calculator .

```

The application will start at: **http://localhost:8000**#### ✅ Test Implementation & ResultsAccept the default options during installation.

### Run Container

```bash

docker run -p 8000:8000 fastapi-calculator

```## 📱 Web Application Features- **Unit Tests**: 35 passing (100% code coverage)



### Using Docker Compose

```bash

docker-compose up### Homepage- **Integration Tests**: 10 passing**Verify Git:**

```

- **URL**: http://localhost:8000

## Logging

- **Features**: Interactive calculator UI- **E2E Tests**: 5 passing

### Configuration

- **Supported Operations**: Add, Subtract, Multiply, Divide

- **Level**: INFO (with DEBUG available)

- **Output**: Console and file (`app.log`)- **Total**: 50 passing tests```bash

- **Format**: `%(asctime)s - %(name)s - %(levelname)s - %(message)s`

### API Endpoints

### Example Output

- **Coverage**: 100% on operations modulegit --version

```

2025-11-02 10:30:15 - app.operations - INFO - Performing addition: 10 + 5#### Addition

2025-11-02 10:30:15 - app.operations - DEBUG - Addition result: 15

2025-11-02 10:30:16 - main - INFO - POST /add - Adding 10.0 + 5.0```bash- **CI/CD**: GitHub Actions workflow successful```

```

curl -X POST "http://localhost:8000/add" \

## Repository Information

  -H "Content-Type: application/json" \

| Property | Value |

|----------|-------|  -d '{"a": 10, "b": 5}'

| **Owner** | kk795-NJIT |

| **Repository** | IS601_Module8 |```## 🚀 Quick Start---

| **URL** | https://github.com/kk795-NJIT/IS601_Module8.git |

| **Branch** | main |**Response**: `{"result": 15}`

| **Visibility** | Public |

| **License** | MIT |



## Learning Outcomes#### Subtraction



This project addresses **CLO10: Create, Consume and Test REST APIs using Python**```bash### 1. Clone the Repository## Configure Git Globals



### Skills Demonstratedcurl -X POST "http://localhost:8000/subtract" \



- ✅ **Created**: RESTful API with FastAPI (4 endpoints)  -H "Content-Type: application/json" \```bash

- ✅ **Consumed**: API endpoints tested via TestClient

- ✅ **Tested**: 50 comprehensive tests with 100% coverage  -d '{"a": 10, "b": 5}'

- ✅ **Designed**: Proper request/response models with Pydantic

- ✅ **Validated**: Input validation and error handling```git clone https://github.com/kk795-NJIT/IS601_Module8.gitSet your name and email so Git tracks your commits properly:

- ✅ **Documented**: API documentation with Swagger/ReDoc

- ✅ **Deployed**: CI/CD automation with GitHub Actions**Response**: `{"result": 5}`

- ✅ **Monitored**: Comprehensive logging and error tracking

cd IS601_Module8

## Code Quality Standards

#### Multiplication

- ✅ PEP 8 Compliant

- ✅ Type Hints Implemented```bash``````bash

- ✅ Docstrings Present

- ✅ Error Handling Comprehensivecurl -X POST "http://localhost:8000/multiply" \

- ✅ DRY Principles Followed

- ✅ SOLID Principles Applied  -H "Content-Type: application/json" \git config --global user.name "Your Name"

- ✅ Security Best Practices

  -d '{"a": 10, "b": 5}'

## Performance Metrics

```### 2. Set Up Python Environmentgit config --global user.email "your_email@example.com"

| Metric | Value |

|--------|-------|**Response**: `{"result": 50}`

| Unit Test Execution Time | ~0.1s |

| Integration Test Execution Time | ~0.7s |```bash```

| E2E Test Execution Time | ~30s |

| Total Test Suite Time | ~31s |#### Division

| Code Coverage | 100% |

| Lines of Code (Operations) | 27 |```bash# Create virtual environment

| Test-to-Code Ratio | 2:1 |

curl -X POST "http://localhost:8000/divide" \

## Troubleshooting

  -H "Content-Type: application/json" \python -m venv venvConfirm the settings:

### Port 8000 Already in Use

```bash  -d '{"a": 10, "b": 2}'

# Kill process on port 8000 (macOS/Linux)

lsof -ti:8000 | xargs kill -9```



# Then restart the application**Response**: `{"result": 5.0}`

python main.py

```# Activate virtual environment```bash



### Virtual Environment Issues#### Division by Zero Error Handling

```bash

# Deactivate current environment```bash# On macOS/Linux:git config --list

deactivate

curl -X POST "http://localhost:8000/divide" \

# Remove and recreate

rm -rf venv  -H "Content-Type: application/json" \source venv/bin/activate```

python -m venv venv

source venv/bin/activate  -d '{"a": 10, "b": 0}'

pip install -r requirements.txt

``````# On Windows:



### Test Failures**Response**: `{"error": "Cannot divide by zero!"}`

```bash

# Run with verbose outputvenv\Scripts\activate---

pytest tests/ -vv

## 🧪 Running Tests

# Run with print statements

pytest tests/ -s```



# Run specific test### Run All Tests

pytest tests/unit/test_calculator.py::test_add_two_positive_integers -v

``````bash## Generate SSH Keys and Connect to GitHub



## Contributingpytest tests/ -v --cov=app --cov-report=html



This is an academic project. For questions or issues, please refer to the GitHub repository.```### 3. Install Dependencies



## License



This project is licensed under the MIT License - see the LICENSE file for details.### Run Unit Tests Only```bash> Only do this once per machine.



## Support```bash



For technical support or questions:pytest tests/unit/ -vpip install -r requirements.txt

1. Review the GitHub Actions workflow status

2. Check application logs in `app.log````

3. Run tests with verbose output for diagnostics

4. Review inline code documentation```1. Generate a new SSH key:



---### Run Integration Tests Only



**Project Status**: Production Ready ✅```bash



**Last Updated**: November 2, 2025pytest tests/integration/ -v



**Version**: 1.0.0```### 4. Run the Application```bash




### Run E2E Tests Only```bashssh-keygen -t ed25519 -C "your_email@example.com"

```bash

pytest tests/e2e/ -vpython main.py```

```

```

### View Coverage Report

```bash(Press Enter at all prompts.)

# Generate coverage report

pytest tests/ --cov=app --cov-report=htmlThe application will start at: **http://localhost:8000**



# Open in browser2. Start the SSH agent:

open htmlcov/index.html

```## 📱 Web Application Features



## 📊 Test Results Summary```bash



### Unit Tests (35 tests)### Homepageeval "$(ssh-agent -s)"

- ✅ Addition operations (5 tests)

- ✅ Subtraction operations (5 tests)- **URL**: http://localhost:8000```

- ✅ Multiplication operations (5 tests)

- ✅ Division operations (6 tests)- **Features**: Interactive calculator UI

- ✅ Edge cases (14 tests: large numbers, zero results, negative numbers, floats)

- **Supported Operations**: Add, Subtract, Multiply, Divide3. Add the SSH private key to the agent:

### Integration Tests (10 tests)

- ✅ API endpoint validation

- ✅ Error handling (division by zero, invalid input)

- ✅ Float number handling### API Endpoints```bash

- ✅ Negative number operations

- ✅ Homepage endpointssh-add ~/.ssh/id_ed25519



### E2E Tests (5 tests)#### Addition```

- ✅ Homepage rendering

- ✅ Addition calculation```bash

- ✅ Subtraction calculation

- ✅ Multiplication calculationcurl -X POST "http://localhost:8000/add" \4. Copy your SSH public key:

- ✅ Division calculation

  -H "Content-Type: application/json" \

### Code Coverage

```  -d '{"a": 10, "b": 5}'- **Mac/Linux:**

app/operations/__init__.py: 100% coverage

- 27 statements```

- 0 missed lines

- 100% coverage**Response**: `{"result": 15}````bash

```

cat ~/.ssh/id_ed25519.pub | pbcopy

## 📝 Logging

#### Subtraction```

### Log Levels

- **INFO**: Operation tracking (e.g., "Performing addition: 10 + 5")```bash

- **DEBUG**: Result tracking (e.g., "Addition result: 15")

- **ERROR**: Error conditions (e.g., "Division by zero attempted")curl -X POST "http://localhost:8000/subtract" \- **Windows (Git Bash):**



### Log Output  -H "Content-Type: application/json" \

Logs are written to:

1. **Console**: Real-time display  -d '{"a": 10, "b": 5}'```bash

2. **File**: `app.log` for persistence

```cat ~/.ssh/id_ed25519.pub | clip

### Example Log Output

```**Response**: `{"result": 5}````

2025-11-02 10:30:15 - app.operations - INFO - Performing addition: 10 + 5

2025-11-02 10:30:15 - app.operations - DEBUG - Addition result: 15

2025-11-02 10:30:16 - main - INFO - POST /add - Adding 10.0 + 5.0

```#### Multiplication5. Add the key to your GitHub account:



## 🔄 CI/CD Pipeline```bash   - Go to [GitHub SSH Settings](https://github.com/settings/keys)



### GitHub Actions Workflowcurl -X POST "http://localhost:8000/multiply" \   - Click **New SSH Key**, paste the key, save.

**File**: `.github/workflows/test.yml`

  -H "Content-Type: application/json" \

**Stages**:

1. **Test Job**  -d '{"a": 10, "b": 5}'6. Test the connection:

   - Checkout code

   - Set up Python 3.10```

   - Install dependencies

   - Run unit tests with coverage**Response**: `{"result": 50}````bash

   - Run integration tests

   - Run E2E testsssh -T git@github.com

   - Upload test results

   - Upload coverage report#### Division```



2. **Security Job**```bash

   - Build Docker image

   - Run Trivy vulnerability scannercurl -X POST "http://localhost:8000/divide" \You should see a success message.

   - Check for critical/high severity issues

  -H "Content-Type: application/json" \

3. **Code Quality Job**

   - Run Pylint checks  -d '{"a": 10, "b": 2}'---

   - Validate code quality

```

**Triggers**:

- ✅ Push to main branch**Response**: `{"result": 5.0}`# 🧩 3. Clone the Repository

- ✅ Pull requests to main branch



**Artifacts**:

- Test results (XML format)#### Division by Zero Error HandlingNow you can safely clone the course project:

- Coverage report (HTML format)

- Retained for 30 days```bash



### Workflow Statuscurl -X POST "http://localhost:8000/divide" \```bash

- **Status**: ✅ Passing

- **Latest Run**: Successful  -H "Content-Type: application/json" \git clone <repository-url>

- **Test Results**: All 50 tests passing

- **Coverage**: 100% on operations module  -d '{"a": 10, "b": 0}'cd <repository-directory>



## 🐳 Docker Support``````



### Build Docker Image**Response**: `{"error": "Cannot divide by zero!"}`

```bash

docker build -t fastapi-calculator .---

```

## 🧪 Running Tests

### Run Container

```bash# 🛠️ 4. Install Python 3.10+

docker run -p 8000:8000 fastapi-calculator

```### Run All Tests



## 📁 Project Structure```bash## Install Python

```

IS601_Module8/pytest tests/ -v --cov=app --cov-report=html

├── main.py                          # FastAPI application

├── app/```- **MacOS (Homebrew)**

│   └── operations/__init__.py        # Calculator functions (100% coverage)

├── templates/

│   └── index.html                   # Frontend UI

├── tests/### Run Unit Tests Only```bash

│   ├── unit/

│   │   └── test_calculator.py        # 35 unit tests```bashbrew install python

│   ├── integration/

│   │   └── test_fastapi_calculator.py # 10 integration testspytest tests/unit/ -v```

│   ├── e2e/

│   │   └── test_e2e.py              # 5 E2E tests```

│   └── conftest.py                  # Test configuration

├── .github/workflows/- **Windows**

│   └── test.yml                     # GitHub Actions workflow

├── requirements.txt                 # Python dependencies### Run Integration Tests Only

├── pytest.ini                       # Pytest configuration

├── Dockerfile                       # Docker configuration```bashDownload and install [Python for Windows](https://www.python.org/downloads/).  

├── README.md                        # This file

└── SUBMISSION_GUIDE.md             # Assignment submission guidepytest tests/integration/ -v✅ Make sure you **check the box** `Add Python to PATH` during setup.

```

```

## 🛠️ Technology Stack

**Verify Python:**

### Backend

- **Framework**: FastAPI 0.115.4### Run E2E Tests Only

- **Web Server**: Uvicorn 0.32.0

- **Validation**: Pydantic 2.9.2```bash```bash

- **Templating**: Jinja2 3.1.4

pytest tests/e2e/ -vpython3 --version

### Testing

- **Unit Tests**: Pytest 8.3.3``````

- **Coverage**: Coverage.py 6.0.0

- **E2E Tests**: Playwright 1.48.0or

- **API Testing**: TestClient (FastAPI built-in)

### View Coverage Report```bash

### CI/CD

- **Platform**: GitHub Actions```bashpython --version

- **Security Scan**: Trivy (aquasecurity/trivy-action)

- **Code Quality**: Pylint 3.3.1# Generate coverage report```

- **Test Reporting**: EnricoMi/publish-unit-test-result-action

pytest tests/ --cov=app --cov-report=html

### Monitoring

- **Logging**: Python logging module---

- **Log Output**: Console + File (app.log)

# Open in browser

## 📈 Performance Metrics

open htmlcov/index.html## Create and Activate a Virtual Environment

### Test Execution Time

- Unit Tests: ~0.1 seconds```

- Integration Tests: ~0.7 seconds

- E2E Tests: ~30 seconds (browser automation)(Optional but recommended)

- Total: ~31 seconds

## 📊 Test Results Summary

### Code Quality

- **Lines of Code**: 27 (operations module)```bash

- **Code Coverage**: 100%

- **Test-to-Code Ratio**: 2:1 (50 tests for 27 LOC)### Unit Tests (35 tests)python3 -m venv venv



## ✨ Key Features- ✅ Addition operations (5 tests)source venv/bin/activate   # Mac/Linux



### Error Handling- ✅ Subtraction operations (5 tests)venv\Scripts\activate.bat  # Windows

- ✅ Division by zero protection

- ✅ Invalid input validation- ✅ Multiplication operations (5 tests)```

- ✅ Comprehensive error messages

- ✅ HTTP status codes (400, 500)- ✅ Division operations (6 tests)



### Data Validation- ✅ Edge cases (14 tests: large numbers, zero results, negative numbers, floats)### Install Required Packages

- ✅ Type checking (int/float)

- ✅ Required field validation

- ✅ Custom error responses

### Integration Tests (10 tests)```bash

### Logging

- ✅ Operation tracking- ✅ API endpoint validationpip install -r requirements.txt

- ✅ Error logging

- ✅ Request/response tracking- ✅ Error handling (division by zero, invalid input)```

- ✅ Performance monitoring

- ✅ Float number handling

### Testing

- ✅ 100% code coverage- ✅ Negative number operations---

- ✅ Edge case testing

- ✅ Integration testing- ✅ Homepage endpoint

- ✅ End-to-end testing

- ✅ Automated CI/CD# 🐳 5. (Optional) Docker Setup



## 🎓 Learning Outcomes Addressed### E2E Tests (5 tests)



### CLO10: Create, Consume and Test REST APIs using Python- ✅ Homepage rendering> Skip if Docker isn't used in this module.

- ✅ **Created**: FastAPI REST API with 4 endpoints

- ✅ **Consumed**: Integration tests verify API endpoints- ✅ Addition calculation

- ✅ **Tested**: 50 comprehensive tests covering all functionality

- ✅ Subtraction calculation## Install Docker

### Additional Skills Demonstrated

- ✅ Test-Driven Development (TDD)- ✅ Multiplication calculation

- ✅ Continuous Integration/Continuous Deployment

- ✅ Professional logging and monitoring- ✅ Division calculation- [Install Docker Desktop for Mac](https://www.docker.com/products/docker-desktop/)

- ✅ Error handling and validation

- ✅ Docker containerization- [Install Docker Desktop for Windows](https://www.docker.com/products/docker-desktop/)

- ✅ Code quality and best practices

### Code Coverage

## 🔗 Repository Information

```## Build Docker Image

- **Owner**: kk795-NJIT

- **Repository**: IS601_Module8app/operations/__init__.py: 100% coverage

- **URL**: https://github.com/kk795-NJIT/IS601_Module8.git

- **Branch**: main- 27 statements```bash

- **Visibility**: Public

- 0 missed linesdocker build -t <image-name> .

## 📞 Support

- 100% coverage```

For issues or questions about this assignment:

1. Check the test output for specific errors```

2. Review the logs in `app.log`

3. Run tests with verbose output: `pytest tests/ -vv`## Run Docker Container

4. Check GitHub Actions for CI/CD details

## 📝 Logging

## ✅ Assignment Completion Checklist

```bash

- ✅ FastAPI Calculator application implemented

- ✅ Unit tests written (35 tests, 100% coverage)### Log Levelsdocker run -it --rm <image-name>

- ✅ Integration tests written (10 tests)

- ✅ E2E tests written (5 tests)- **INFO**: Operation tracking (e.g., "Performing addition: 10 + 5")```

- ✅ Comprehensive logging implemented

- ✅ Git version control with descriptive commits- **DEBUG**: Result tracking (e.g., "Addition result: 15")

- ✅ GitHub Actions CI/CD configured and working

- ✅ README documentation provided- **ERROR**: Error conditions (e.g., "Division by zero attempted")---

- ✅ SUBMISSION_GUIDE provided

- ✅ All tests passing (50/50)

- ✅ Web application running successfully

- ✅ Error handling implemented### Log Output# 🚀 6. Running the Project

- ✅ Professional code quality standards met

Logs are written to:

## 🎉 Project Status

1. **Console**: Real-time display- **Without Docker**:

**Status**: ✅ **COMPLETE AND READY FOR SUBMISSION**

2. **File**: `app.log` for persistence

All assignment requirements have been met with professional-grade implementation.

```bash

See [SUBMISSION_GUIDE.md](SUBMISSION_GUIDE.md) for submission instructions and screenshots.

### Example Log Outputpython main.py

---

``````

**Last Updated**: November 2, 2025

**Version**: 1.02025-11-02 10:30:15 - app.operations - INFO - Performing addition: 10 + 5

**Status**: Production Ready

2025-11-02 10:30:15 - app.operations - DEBUG - Addition result: 15(or update this if the main script is different.)

2025-11-02 10:30:16 - main - INFO - POST /add - Adding 10.0 + 5.0

```- **With Docker**:



## 🔄 CI/CD Pipeline```bash

docker run -it --rm <image-name>

### GitHub Actions Workflow```

**File**: `.github/workflows/test.yml`

---

**Stages**:

1. **Test Job**# 📝 7. Submission Instructions

   - Checkout code

   - Set up Python 3.10After finishing your work:

   - Install dependencies

   - Run unit tests with coverage```bash

   - Run integration testsgit add .

   - Run E2E testsgit commit -m "Complete Module X"

   - Upload test resultsgit push origin main

   - Upload coverage report```



2. **Security Job**Then submit the GitHub repository link as instructed.

   - Build Docker image

   - Run Trivy vulnerability scanner---

   - Check for critical/high severity issues

# 🔥 Useful Commands Cheat Sheet

3. **Code Quality Job**

   - Run Pylint checks| Action                         | Command                                          |

   - Validate code quality| ------------------------------- | ------------------------------------------------ |

| Install Homebrew (Mac)          | `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` |

**Triggers**:| Install Git                     | `brew install git` or Git for Windows installer |

- ✅ Push to main branch| Configure Git Global Username  | `git config --global user.name "Your Name"`      |

- ✅ Pull requests to main branch| Configure Git Global Email     | `git config --global user.email "you@example.com"` |

| Clone Repository                | `git clone <repo-url>`                          |

**Artifacts**:| Create Virtual Environment     | `python3 -m venv venv`                           |

- Test results (XML format)| Activate Virtual Environment   | `source venv/bin/activate` / `venv\Scripts\activate.bat` |

- Coverage report (HTML format)| Install Python Packages        | `pip install -r requirements.txt`               |

- Retained for 30 days| Build Docker Image              | `docker build -t <image-name> .`                |

| Run Docker Container            | `docker run -it --rm <image-name>`               |

### Workflow Status| Push Code to GitHub             | `git add . && git commit -m "message" && git push` |

- **Status**: ✅ Passing

- **Latest Run**: Successful---

- **Test Results**: All 50 tests passing

- **Coverage**: 100% on operations module# 📋 Notes



## 🐳 Docker Support- Install **Homebrew** first on Mac.

- Install and configure **Git** and **SSH** before cloning.

### Build Docker Image- Use **Python 3.10+** and **virtual environments** for Python projects.

```bash- **Docker** is optional depending on the project.

docker build -t fastapi-calculator .

```---



### Run Container# 📎 Quick Links

```bash

docker run -p 8000:8000 fastapi-calculator- [Homebrew](https://brew.sh/)

```- [Git Downloads](https://git-scm.com/downloads)

- [Python Downloads](https://www.python.org/downloads/)

## 📁 Project Structure- [Docker Desktop](https://www.docker.com/products/docker-desktop/)

```- [GitHub SSH Setup Guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

IS601_Module8/
├── main.py                          # FastAPI application
├── app/
│   └── operations/__init__.py        # Calculator functions (100% coverage)
├── templates/
│   └── index.html                   # Frontend UI
├── tests/
│   ├── unit/
│   │   └── test_calculator.py        # 35 unit tests
│   ├── integration/
│   │   └── test_fastapi_calculator.py # 10 integration tests
│   ├── e2e/
│   │   └── test_e2e.py              # 5 E2E tests
│   └── conftest.py                  # Test configuration
├── .github/workflows/
│   └── test.yml                     # GitHub Actions workflow
├── requirements.txt                 # Python dependencies
├── pytest.ini                       # Pytest configuration
├── Dockerfile                       # Docker configuration
└── README.md                        # This file
```

## 🛠️ Technology Stack

### Backend
- **Framework**: FastAPI 0.115.4
- **Web Server**: Uvicorn 0.32.0
- **Validation**: Pydantic 2.9.2
- **Templating**: Jinja2 3.1.4

### Testing
- **Unit Tests**: Pytest 8.3.3
- **Coverage**: Coverage.py 6.0.0
- **E2E Tests**: Playwright 1.48.0
- **API Testing**: TestClient (FastAPI built-in)

### CI/CD
- **Platform**: GitHub Actions
- **Security Scan**: Trivy (aquasecurity/trivy-action)
- **Code Quality**: Pylint 3.3.1
- **Test Reporting**: EnricoMi/publish-unit-test-result-action

### Monitoring
- **Logging**: Python logging module
- **Log Output**: Console + File (app.log)

## 📈 Performance Metrics

### Test Execution Time
- Unit Tests: ~0.1 seconds
- Integration Tests: ~0.7 seconds
- E2E Tests: ~30 seconds (browser automation)
- Total: ~31 seconds

### Code Quality
- **Lines of Code**: 27 (operations module)
- **Code Coverage**: 100%
- **Test-to-Code Ratio**: 2:1 (50 tests for 27 LOC)

## ✨ Key Features

### Error Handling
- ✅ Division by zero protection
- ✅ Invalid input validation
- ✅ Comprehensive error messages
- ✅ HTTP status codes (400, 500)

### Data Validation
- ✅ Type checking (int/float)
- ✅ Required field validation
- ✅ Custom error responses

### Logging
- ✅ Operation tracking
- ✅ Error logging
- ✅ Request/response tracking
- ✅ Performance monitoring

### Testing
- ✅ 100% code coverage
- ✅ Edge case testing
- ✅ Integration testing
- ✅ End-to-end testing
- ✅ Automated CI/CD

## 🎓 Learning Outcomes Addressed

### CLO10: Create, Consume and Test REST APIs using Python
- ✅ **Created**: FastAPI REST API with 4 endpoints
- ✅ **Consumed**: Integration tests verify API endpoints
- ✅ **Tested**: 50 comprehensive tests covering all functionality

### Additional Skills Demonstrated
- ✅ Test-Driven Development (TDD)
- ✅ Continuous Integration/Continuous Deployment
- ✅ Professional logging and monitoring
- ✅ Error handling and validation
- ✅ Docker containerization
- ✅ Code quality and best practices

## 🔗 Repository Information

- **Owner**: kk795-NJIT
- **Repository**: IS601_Module8
- **URL**: https://github.com/kk795-NJIT/IS601_Module8.git
- **Branch**: main
- **Visibility**: Public

## 📞 Support

For issues or questions about this assignment:
1. Check the test output for specific errors
2. Review the logs in `app.log`
3. Run tests with verbose output: `pytest tests/ -vv`
4. Check GitHub Actions for CI/CD details

## ✅ Assignment Completion Checklist

- ✅ FastAPI Calculator application implemented
- ✅ Unit tests written (35 tests, 100% coverage)
- ✅ Integration tests written (10 tests)
- ✅ E2E tests written (5 tests)
- ✅ Comprehensive logging implemented
- ✅ Git version control with descriptive commits
- ✅ GitHub Actions CI/CD configured and working
- ✅ README documentation provided
- ✅ All tests passing (50/50)
- ✅ Web application running successfully
- ✅ Error handling implemented
- ✅ Professional code quality standards met

## 🎉 Project Status

**Status**: ✅ **COMPLETE AND READY FOR SUBMISSION**

All assignment requirements have been met with professional-grade implementation.

---

**Last Updated**: November 2, 2025
**Version**: 1.0
**Status**: Production Ready
