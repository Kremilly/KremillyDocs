---
Title: PageShot
Category: Crate
Description: Capture screenshots of web pages from specified URL using Rust. Customize viewport dimensions and save the resulting image in PNG format. You can customize the viewport dimensions and save the resulting image in PNG format.
Package: cargo install pageshot
---
![img](https://img.shields.io/crates/v/pageshot?style=flat-square&logo=rust)

# PageShot

Capture screenshots of web pages from specified URL using Rust. Customize viewport dimensions and save the resulting image in PNG format. You can customize the viewport dimensions and save the resulting image in PNG format.

## Features

- Capture screenshots from any URL.
- Customize viewport width and height.
- Save screenshots in PNG format.
- Simple command-line interface.

## Installation

To Install using [crates.io](https://crates.io/):

> cargo install pageshot

## Usage

Run the compiled binary with the desired URL, viewport dimensions, and output file name:

```sh
pageshot -u https://example.com --width 1920 --height 1080 -o example.png
```

### Arguments

- `-u, --url <URL>`: The URL of the web page to capture.
- `--width <WIDTH>`: The width of the viewport (default: 1920).
- `--height <HEIGHT>`: The height of the viewport (default: 1080).
- `-o, --output <FILE>`: The name of the output file (default: `screenshot.png`).
