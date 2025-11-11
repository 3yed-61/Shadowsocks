# Shadowsocks Config Cleaner

## Introduction

This project provides a Python-based tool for processing and cleaning
Shadowsocks configuration files. It is designed for users who need to
sanitize, validate, and standardize Shadowsocks JSON configs collected
from different sources.

## Features

-   Batch processing of multiple config files
-   Removal of unused or redundant fields
-   Detection of invalid entries (e.g., malformed IP addresses or
    domains)
-   Produces clean, standardized JSON output
-   Simple command-line interface
-   Fully written in Python and easy to extend

## Requirements

-   Python 3.8+

-   Install dependencies:

    ``` bash
    pip install -r requirements.txt
    ```

## Installation

Clone the repository:

``` bash
git clone https://github.com/3yed-61/Shadowsocks.git
cd Shadowsocks
```

(Optional) Create a virtual environment:

``` bash
python3 -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate   # Windows
```

Install dependencies:

``` bash
pip install -r requirements.txt
```

## Usage

Run the cleaner script:

``` bash
python config-cleaner.py --input path/to/configs --output cleaned/configs.json
```

Arguments: - `--input`: Path to a folder or a single JSON file -
`--output`: Output file path - Additional future flags may include
`--validate` and `--verbose`

## Example

``` bash
python config-cleaner.py --input raw-configs --output cleaned/configs.json
```

## Development

1.  Fork the repository\

2.  Create a feature branch:

    ``` bash
    git checkout -b feature/my-new-feature
    ```

3.  Make your changes and commit\

4.  Submit a pull request

## Contributing

Contributions are welcome.\
Before submitting a pull request: - Provide a clear description of your
changes - Add tests if applicable - Ensure your code matches the project
structure and style

## License

This project is released under the Apache License 2.0.\
See the `LICENSE` file for details.

## Contact

If you encounter issues or have suggestions, please open an Issue in the
repository.
