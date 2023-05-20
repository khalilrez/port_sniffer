# CLI Port Sniffer in Rust

This command-line tool allows you to scan a host for open ports. It utilizes multithreading to enhance the scanning performance. This readme provides an overview of the code and instructions for running the CLI Port Sniffer.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The CLI Port Sniffer is implemented in Rust and provides a simple way to scan a specified host for open ports. It utilizes TCP connections to check the accessibility of each port. The tool supports multithreading to expedite the scanning process and provide faster results.

## Installation

To install and run the CLI Port Sniffer, follow these steps:

1. Install Rust: If you haven't installed Rust yet, you can do so by following the instructions at [https://www.rust-lang.org](https://www.rust-lang.org).
2. Clone the repository or download the source code for the CLI Port Sniffer.
3. Open a terminal or command prompt and navigate to the project directory.

## Usage

To use the CLI Port Sniffer, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the directory containing the CLI Port Sniffer code.
3. Run the following command to build the project:

   `cargo build --release`

4. After a successful build, run the following command to start the port scanning process:

   `cargo run -- <arguments>`

   Replace `<arguments>` with the desired command-line arguments. The available options are:

   - `-h` or `--help`: Displays the help message, providing information about the available options and their usage.

   - `-j` or `--threads`: Specifies the number of threads to use for port scanning. It expects an additional argument indicating the number of threads to be used. For example: `cargo run -- --threads 4` to scan the host using four threads.

5. The CLI Port Sniffer will start scanning the specified host for open ports. Once the scan is complete, the tool will display the open ports found.

## Contributing

Contributions to this project are welcome. If you have suggestions, bug reports, or would like to contribute to the development of the CLI Port Sniffer, please follow the standard procedure of forking the repository and submitting a pull request. Your contributions will be reviewed and merged if deemed appropriate.

## License

The content of this repository is licensed under the MIT License. You are free to use the code and content as a reference or for personal projects. However, please be mindful of the license and respect any third-party libraries or dependencies used in the project.

If you have any questions or need assistance, please feel free to reach out.
