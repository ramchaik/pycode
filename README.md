# PyCode

PyCode is a simple CLI application that generates the code and tests for your desired language and task. It uses Large Language Model (LLM) for the generation of code and tests.

## Running the application

Install the required dependencies

```shell
pip install
```

_NOTE: Please set the GOOGLE_API_KEY environment variable, you will need to generate the key. You can also create a .env file with the same._

Below command will generate a javascript code that prints hello

```shell
python main.py --task 'print hello' --language js
```

#### Output

![JS Generated Code](/docs/js_generated.png)

Running with no arguments will return result with default values

```shell
# This will use the default values
python main.py 
```

#### Output
![PY Generated Code](/docs/py_generated.png)
