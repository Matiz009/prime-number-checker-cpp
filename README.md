# Prime Number Checker (C++)

A beginner C++ program that asks for a number and says whether it is prime.

## Features

- Reads a number from the user and prints whether it is prime

> **Known issue (TODO):** the check is `a % 2 == 1`, which tests whether the number is odd, not whether it is prime. So 9 is reported as prime and 2 as not prime.

## Tech stack

C++

## Getting started

```bash
git clone https://github.com/Matiz009/prime-number-checker-cpp.git
cd prime-number-checker-cpp
g++ "primeNumber.cpp" -o primeNumber && ./primeNumber
```

## Project structure

```
primeNumber.cpp   Source code
primeNumber.exe   Old Windows build
```

## Author

**Mati ul Rehman** - [github.com/Matiz009](https://github.com/Matiz009)
