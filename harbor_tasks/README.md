# Line and Word Count Task

This project implements a simple Harbor task that counts the number of lines and words in a text file.

## Project Structure

line-word-count/
├── environment/
│ ├── input.txt
│ └── output.txt
├── solution/
│ └── solve.sh
├── tests/
│ ├── test.sh
│ └── test_outputs.py
├── task.toml
└── instruction.md


## How It Works

- The input file is located at `environment/input.txt`
- The script counts:
  - Total number of lines
  - Total number of words
- The result is written to `environment/output.txt`

## How to Run Locally

From the `line-word-count` directory, run:

```bash
chmod +x solution/solve.sh
./solution/solve.sh

Output

After running the script, the output will be available at:

environment/output.txt


Example output:

    Lines: 3
    Words: 10

Notes

This solution follows the Harbor task specification and is compatible with container-based execution.

---
