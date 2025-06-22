# openafter

## Purpose

`openafter` is a simple command-line utility that opens a specified URL or file after a given delay, without blocking the terminal.

## Usage

```bash
openafter <delay_seconds> <target>
```

*   `<delay_seconds>`: The number of seconds to wait before opening the target.
*   `<target>`: The URL or file path to open.

## Examples

1.  Open Google's homepage after 5 seconds:

    ```bash
    openafter 5 https://www.google.com
    ```

2.  Open a local file named `document.pdf` after 10 seconds:

    ```bash
    openafter 10 document.pdf
    ```

## Installation

No installation is required. Simply save the script to a directory in your `PATH` and make it executable:

```bash
chmod +x openafter
```

## Banner

![Banner Image](banner.jpg)