# NumPy Test for Serverless

Testing NumPy and Python packaging for AWS Lambda

## Prerequisites

- Node version: 12.16.0

- Python version: 3.7.6

- Serverless version: 1.63.0

- Lint: PyLint w/ Black

## Project setup

```bash
# Install dependencies
pip3 install -r requirements.txt

or

pipenv install

# Compiling for Serverless development
sls deploy

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
