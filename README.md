# Collatz Verification Script

This Python script verifies that all integers from 2 to 1173 converge to 1 under the modified Collatz map:

- If \( n \) is even: \( n \to n / 2 \)
- If \( n \) is odd: \( n \to (3n + 1) / 2 \)

## Usage

No dependencies are required. To run:

```bash
python3 collatz_verify.py
