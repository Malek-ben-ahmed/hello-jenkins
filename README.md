# Hello Jenkins 🚀

This is a simple project created to test Jenkins CI/CD pipelines.  
The project contains a basic script and a Jenkins pipeline to demonstrate build, test, and deploy stages

## Project Structure
- `main.py` → simple Python script printing "Hello Jenkins"
- `test_main.py` → basic test using pytest
- `Jenkinsfile` → defines the CI/CD pipeline

## Pipeline Stages
1. **Build**: Runs the Python script  
2. **Test**: Executes pytest on the test file  
3. **Deploy**: Simulates a deployment step

## How to Run Locally
```bash
python3 main.py
pytest test_main.py
