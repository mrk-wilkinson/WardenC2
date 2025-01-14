# WardenC2

A WIP C2 server.

## Introduction

WardenC2 is a work-in-progress Command and Control (C2) server designed to manage and control multiple agents remotely. This project aims to provide a robust and flexible solution for C2 operations.

## Installation

To install WardenC2, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/mrk-wilkinson/WardenC2.git
   ```
2. Navigate to the project directory:
   ```bash
   cd WardenC2
   ```
3. Setup PrisonYard (Listening post)
   ```bash
   # Example for a Python project
   cd PrisonYard && cargo run
   ```

## Usage

To start using WardenC2, follow these instructions:

1. Configure implant settings
   ```bash
   cd Inmates
   # Not yet setup
   ```
3. Deploy implants to target.

## Components

- [ ] PrisonYard: Listening post written in rust.  Runs api for implants and for operator.  Stores implant info in sqlite datbase and uses artifact directory to store c2 responses.
- [ ] Jailer: CLI interface for operating the server.  Connects to PrisonYard operator api.
- [ ] Justice: Library with structures for requests, responses, and implant information.
- [ ] Inmates: Submodule containing different implants.  Currently only has one implant.

## Contributing

Contributions are welcome! 

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Disclaimer
This project is only intended for legally authorized adversary emulation and penetration testing. The author reserves no liability for how others use this tool.
