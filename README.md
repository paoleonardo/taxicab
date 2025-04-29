# 🚖 Taxicab Numbers and Their Prime Factorization

Welcome to the **Taxicab** repository! This project explores taxicab numbers up to T(10) and provides their prime factor decomposition. Taxicab numbers have fascinated mathematicians for years, and this repository aims to make their properties accessible and understandable.

[![Download Releases](https://img.shields.io/badge/Download%20Releases-blue.svg)](https://github.com/paoleonardo/taxicab/releases)

## Table of Contents

1. [Introduction](#introduction)
2. [What are Taxicab Numbers?](#what-are-taxicab-numbers)
3. [Prime Factor Decomposition](#prime-factor-decomposition)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)
8. [Acknowledgments](#acknowledgments)

## Introduction

Taxicab numbers arise from a famous anecdote involving mathematician Srinivasa Ramanujan. He famously stated that 1729 is the smallest number expressible as the sum of two cubes in two different ways. This project explores these numbers and provides tools for their prime factorization.

In this repository, you will find code and resources to calculate taxicab numbers and their prime factors. 

## What are Taxicab Numbers?

Taxicab numbers, denoted as T(n), represent the smallest number that can be expressed as the sum of two cubes in n distinct ways. The first few taxicab numbers are:

- T(1) = 1
- T(2) = 8
- T(3) = 27
- T(4) = 64
- T(5) = 125
- T(6) = 216
- T(7) = 729
- T(8) = 1729
- T(9) = 4104
- T(10) = 13832

These numbers hold a special place in number theory and have applications in various mathematical fields.

## Prime Factor Decomposition

Understanding the prime factorization of taxicab numbers adds another layer of insight. Each taxicab number can be expressed as a product of prime numbers. For example:

- T(2) = 8 = 2³
- T(3) = 27 = 3³
- T(4) = 64 = 2⁶

This project provides functions to calculate the prime factorization of each taxicab number, enabling deeper analysis and understanding.

## Installation

To get started with the Taxicab project, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/paoleonardo/taxicab.git
   cd taxicab
   ```

2. **Install Dependencies:**

   Ensure you have Python installed. You can use pip to install any necessary packages. For example:

   ```bash
   pip install -r requirements.txt
   ```

3. **Download Releases:**

   For the latest version, visit the [Releases section](https://github.com/paoleonardo/taxicab/releases) to download the necessary files. Execute the downloaded file to get started.

## Usage

Once you have installed the project, you can begin using it to explore taxicab numbers and their prime factors.

### Example Code

Here is a simple example to get you started:

```python
from taxicab import Taxicab

# Create an instance of Taxicab
taxicab = Taxicab()

# Get the first 10 taxicab numbers
for i in range(1, 11):
    print(f"T({i}) = {taxicab.get_taxicab_number(i)}")
    print(f"Prime Factors of T({i}): {taxicab.get_prime_factors(i)}")
```

### Output

When you run the above code, you will see the taxicab numbers and their prime factors printed to the console.

## Contributing

We welcome contributions! If you want to improve this project, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

Your contributions help make this project better for everyone.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

We acknowledge the contributions of mathematicians and researchers who have explored taxicab numbers and prime factorization. Their work inspires us to delve deeper into these fascinating concepts.

---

Thank you for exploring the Taxicab project! We hope you find it useful and informative. For more information, visit the [Releases section](https://github.com/paoleonardo/taxicab/releases) to download the latest updates.