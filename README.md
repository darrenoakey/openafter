# openafter

## Purpose

The `openafter` script opens a specified URL or file after a given delay, without blocking the current terminal.

## Usage

`openafter <delay_seconds> <target>`

*   `<delay_seconds>`: The number of seconds to wait before opening the target.
*   `<target>`: The URL or file path to open.

## Examples

*   Open Google's homepage after 5 seconds:

    `openafter 5 "https://www.google.com"`

*   Open a local file named `document.pdf` after 10 seconds:

    `openafter 10 "document.pdf"`

## Installation

1.  Save the script to a file named `openafter`.
2.  Make the script executable:

    `chmod +x openafter`

3.  (Optional) Move the script to a directory in your `$PATH` (e.g., `/usr/local/bin`) to make it accessible from anywhere.

## Banner

![Banner Image](banner.jpg)
