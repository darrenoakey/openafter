# openafter

## Purpose

`openafter` opens a specified URL or file after a given delay, without blocking the terminal.

## Usage

```
openafter <delay_seconds> <target>
```

*   `<delay_seconds>`:  The number of seconds to wait before opening the target.
*   `<target>`: The URL or file to open.

## Examples

*   Open a website after 5 seconds:

    ```sh
    openafter 5 https://www.example.com
    ```

*   Open a local file after 10 seconds:

    ```sh
    openafter 10 /path/to/your/file.txt
    ```

## Installation

1.  Save the script to a file named `openafter`.
2.  Make the script executable:

    ```sh
    chmod +x openafter
    ```

3.  (Optional) Move the script to a directory in your `PATH` (e.g., `/usr/local/bin`) to make it accessible from anywhere.

## Banner

![Banner Image](banner.jpg)