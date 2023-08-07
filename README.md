# NumPy Test for Serverless

Testing NumPy and Python packaging for AWS Lambda

## Prerequisites

- Node version: 18.x.x

- Python version: 3.10.x

- Serverless version: 3.x.x

- Lint: PyLint w/ Black

## Project setup

```bash
# Install dependencies
pip3 install -r requirements.txt

# or install with pipenv==2023.7.4
pipenv install

# Configure serverless.yml
serverless.yml

# Compiling for Serverless development
serverless deploy --verbose

# Run your tests
pytest

# Lints and fixes files
pylint
```

## NumPy Test Invoke

```bash
serverless invoke -f numpy --log
```

## License

None
