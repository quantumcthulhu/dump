# Dump Sources To The Clipboard

This script scans the current directory (and subdirectories) for files with specific extensions, formats their content, and copies the output to the clipboard (if possible) to use in a prompt in LLM interface like ChatGPT. By default it searches for all source files, but you can pass custom extensions as command\-line arguments.

## Installation

1. Clone the repository.
   ```bash
   git clone https://github.com/quantumcthulhu/dump
   ```
3. Install required dependencies:

    ```bash
    cd dump && pip install -r requirements.txt
    ```
4. Install

   ```bash
   chmod +x dump && cp dump ~/.local/bin
   ```

## Usage

Run the script to search for source files:

```bash
dump
```

To search for other file extensions, pass them as arguments:

```bash
dump .txt .md .html
```
