
# SSH Key Generator

A simple shell function to generate SSH keys with user-defined parameters.

## Overview

The `generate_ssh_key` function allows users to easily generate SSH keys by prompting for key type, bit size (for RSA), comment, and file path to save the key. After key generation, users also have the option to view the public key.

## Requirements

- Bash or Zsh shell
- `ssh-keygen` utility (typically comes pre-installed on Unix-based systems)

## Usage

1. Source the function in your shell:

   ```bash
   source /path/to/script
   ```

   Note: You can add the function to your `~/.bashrc` or `~/.zshrc` to make it available in every new terminal session.

2. Call the function:

   ```bash
   generate_ssh_key
   ```

3. Follow the prompts to generate your SSH key.

## Functionality

- Prompts user for:
  - Key type (RSA or ED25519)
  - Bit size (2048 or 4096) if RSA is chosen
  - Comment or email
  - File path to save the key

- Generates the SSH key based on the provided inputs.
- Offers an option to display the generated public key.

## License

This script is provided under the MIT License. The terms of the license can be found within the script itself or at [the official MIT License webpage](https://opensource.org/licenses/MIT).
