# Windows Terminal

This project is a simple web-based terminal emulator that mimics the look and feel of a Windows command prompt. It supports basic commands and allows users to interact with it through a text input field.

## Features

- **Basic Commands**: Supports basic commands like `help`, `clear`, `echo`, `time`, `date`, `history`, `color`, and `resetcolor`.
- **Command History**: Navigate through previously entered commands using the up and down arrow keys.
- **Customizable Text Color**: Change the terminal text color using the `color` command and reset it to the default green color using the `resetcolor` command.

## Available Commands

- `help`: Show available commands.
- `clear`: Clear the terminal output.
- `echo [text]`: Print the specified text.
- `time`: Show the current time.
- `date`: Show the current date.
- `history`: Show the list of previously entered commands.
- `color [color]`: Change the terminal text color to the specified color.
- `resetcolor`: Reset the terminal text color to the default green color.

## Usage

1. Open the `Terminal.html` file in a web browser.
2. Type commands into the input field and press `Enter` to execute them.
3. Use the up and down arrow keys to navigate through the command history.

Deployment Link: [Terminal](https://alienminus.github.io/Terminal/)

## Example

```sh
C:\Users\minus> help
Available commands:
help - Show available commands
clear - Clear terminal
echo [text] - Print text
time - Show current time
date - Show current date
history - Show command history
color [color] - Change text color
resetcolor - Reset text color to default

C:\Users\minus> echo Hello, World!
Hello, World!

C:\Users\minus> time
Current Time: 10:30:00 AM

C:\Users\minus> date
Current Date: 3/14/2025

C:\Users\minus> color red
Text color changed to red

C:\Users\minus> resetcolor
Text color reset to default

**License**
This project is licensed under the MIT License.