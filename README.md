# WebGuard
This project is a simple, lightweight Python script designed to block specific websites on a browser locally. It modifies system files to restrict access to certain URLs, ensuring that the selected sites are inaccessible from the user's machine. Ideal for productivity, parental control, or self-imposed web limitations.

# Python Website Blocker

A minimal Python script to block websites on your local machine by modifying system files. This tool is useful for improving productivity, implementing parental controls, or restricting access to certain websites.

## Features

- Block any website by adding its URL to the block list.
- Modify the hosts file to prevent access to specific websites.
- Simple and lightweight script with no external dependencies.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/WebGuard.git
    ```
2. Navigate to the project directory:
    ```bash
    cd WebGuard
    ```

## Usage

1. Open the `WebGuard.py` script.
2. Add the websites you want to block to the `sites_to_block` list:
    ```python
    sites_to_block = ["www.example.com", "www.anotherexample.com"]
    ```
3. Run the script as an administrator:
    ```bash
    python WebGuard.py
    ```
