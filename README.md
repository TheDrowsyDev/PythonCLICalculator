# PythonCLICalculator
Simple CLI Calculator in Python

This application serves as a basic introduction to building a CLI application with `argparse` in Python. All the code is located in `src/main.py`.

Please feel free to submit any question or comments as issues. Happy coding!

## Usage
```
usage: main.py [-h] {add,subtract,multiply,divide} num_one num_two

positional arguments:
  {add,subtract,multiply,divide}
                        The operation to run on the given arguments.
  num_one               The first number.
  num_two               The second number.

options:
  -h, --help            show this help message and exit
```

Add:
```
python3 main.py add 1.0 5.0
Result: 6.0
```

Subtract:
```
python3 main.py subtract 5.0 3.0
Result: 2.0
```

Multiply:
```
python3 main.py multiply 5 5
Result: 25.0
```

Divide:
```
python3 main.py divide 9.0 3.0
Result: 3.0
```