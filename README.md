![](banner.jpg)

# openafter

## Purpose

The `openafter` script opens a specified URL or file after a given delay, without blocking the terminal.

## Usage

`openafter <delay_seconds> <target>`

*   `<delay_seconds>`: The number of seconds to wait before opening the target.
*   `<target>`: The URL or file path to open.

## Examples

1.  Open a URL after a 5-second delay:

    `openafter 5 https://www.example.com`

2.  Open a file after a 10-second delay:

    `openafter 10 /path/to/your/file.txt`

## Installation

1.  Save the script to a file named `openafter`.
2.  Make the script executable:

    `chmod +x openafter`

3.  (Optional) Move the script to a directory in your `$PATH` (e.g., `/usr/local/bin`) to make it accessible from anywhere in the terminal:

    `sudo mv openafter /usr/local/bin`