# Go Interpreter Project

![Go Version](https://img.shields.io/badge/Go-1.23.1-blue.svg)
![Test Coverage](https://img.shields.io/badge/Coverage-72%25-yellowgreen.svg)

## Description
This project implements an interpreter for a custom programming language with implicit typing, similar to Python. It features a Read-Eval-Print Loop (REPL) for interactive execution of code.

## Features
- REPL (Read-Eval-Print Loop) interface
- Implicit typing system
- Custom language syntax

## Installation
To use this interpreter, you need Go 1.23.1 installed on your system.

Clone the repository:
```bash
git clone https://github.com/ddelvalfraire/interpreter
cd interpreter
```

## Usage
To start the REPL:
```bash
go run main.go
```

Once in the REPL, you can start typing expressions in the custom language. The interpreter will evaluate them and print the results.

Example:
```
>> let x = 5
>> x
5
>> let y = 10
>> y
10
>> x + y
15
```

## Testing
To run the tests:
```bash
go test ./...
```

## License
This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
