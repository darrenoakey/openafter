# openafter

## Purpose

The `openafter` script opens a specified URL or file after a given delay, without blocking the terminal.

## Usage

```bash
openafter <delay_seconds> <target>
```

*   `<delay_seconds>`:  The number of seconds to wait before opening the target.
*   `<target>`: The URL or file path to open.

## Examples

1.  Open a website after 5 seconds:

    ```bash
    openafter 5 https://www.example.com
    ```

2.  Open a local file after 10 seconds:

    ```bash
    openafter 10 /path/to/your/file.txt
    ```

## Installation

1.  Save the script to a file named `openafter`.
2.  Make the script executable:

    ```bash
    chmod +x openafter
    ```

3.  (Optional) Move the script to a directory in your `$PATH` (e.g., `/usr/local/bin`) to make it accessible from anywhere in the terminal.

## Banner

![Banner Image](banner.jpg)
