# ShadowJS

**ShadowJS** is a fast, lightweight JavaScript obfuscator built with Rust. It protects your code by converting readable identifiers into obscure formats, ensuring security without sacrificing performance. Whether you are protecting proprietary logic or preventing tampering, ShadowJS delivers robust obfuscation with minimal overhead.

## Features

- **Fast and Lightweight**: Built with Rust for maximum performance and efficiency.
- **Security Focused**: Helps protect your code from tampering by converting identifiers into cryptic formats.
- **Easy to Use**: Command-line interface for quick and simple integration.

## Installation

To Install using [crates.io](https://crates.io/):

```bash
cargo install shadowjs
```

## Usage

You can run **ShadowJS** from the command line by providing the path to the input and output JavaScript files. Here's how to use it:

### Command Syntax

```bash
shadowjs <input.js> <output.js>
```

- **input.js**: The path to the JavaScript file you want to obfuscate.
- **output.js**: The path where the obfuscated JavaScript file will be saved.

### Example

```bash
shadowjs input.js output.min.js
```

This command will obfuscate `input.js` and save the result in `output.min.js`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
