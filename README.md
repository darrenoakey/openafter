# openafter

## Purpose

`openafter` opens a specified URL or file after a given delay, without blocking the current terminal.

## Usage

```bash
openafter <delay_seconds> <target>
```

*   `<delay_seconds>`: The number of seconds to wait before opening the target.
*   `<target>`: The URL or file path to open.

## Examples

1.  Open Google's website after a 5-second delay:

    ```bash
    openafter 5 https://www.google.com
    ```

2.  Open a local file named `document.pdf` after a 10-second delay:

    ```bash
    openafter 10 document.pdf
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