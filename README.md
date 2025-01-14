# Crax
The Crax project is a command-line interface (CLI) tool written in Rust, designed to interact with OpenAI APIs. It provides multiple features such as interactive chatting, text translation, generating commit messages, writing code, and debugging code.

## Features
- Interactive Chat: Engage in an interactive chat session.
- Translate: Translate text from a specified file.
- Generate Commit Message: Automatically generate a commit message for a given change.
- Write Code: Generate code based on a given prompt.
- Debug Code: Debug code with a specified issue.
- Installation
- Clone the repository and build the project:

## Installation
To use this CLI, follow these steps:
1. Clone the repository:
```
git clone https://github.com/kunaltelangi/Crax
```

2. Change directory to the repository:
```
cd Crax
```

4. Build the CLI using Cargo:
```
cargo build --release
```

## Usage

The CLI provides two modes of operation: interactive mode and single prompt mode.

### Start Interactive Chat

```bash
cargo run -- chat
```

### Translate Text

```bash
cargo run -- translate <path-to-text-file>
```

### Generate Commit Message

```bash
cargo run -- commit-message <path-to-file>
```

### Write Code

```bash
cargo run -- code <prompt>
```

### Debug Code

```bash
cargo run -- debug <path-to-file> <issue>
```

## Dependencies
- Rust: The Rust programming language.

- Clap: For command-line argument parsing.

- Tokio: For asynchronous runtime support.

## Example 
https://github.com/user-attachments/assets/112d9d0b-39c5-4a1b-aa43-f20760215d87


Ensure that you have the necessary permissions and access to the specified files when running these commands.

# License
This project is licensed under the MIT License. See the LICENSE file for more details.

