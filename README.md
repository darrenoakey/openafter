# openafter

## Purpose

`openafter` opens a specified URL or file after a given delay, without blocking the terminal.

## Usage

```
openafter <delay_seconds> <target>
```

*   `<delay_seconds>`: The number of seconds to wait before opening the target.
*   `<target>`: The URL or file path to open.

## Examples

1.  Open Google's homepage after 5 seconds:

    ```sh
    openafter 5 "https://www.google.com"
    ```

2.  Open a local file named `document.pdf` after 10 seconds:

    ```sh
    openafter 10 "document.pdf"
    ```

## Installation

This script requires no specific installation steps. Simply save the script to a directory in your `PATH` and make it executable:

```sh
chmod +x openafter
```

## Banner

![Banner Image](banner.jpg)