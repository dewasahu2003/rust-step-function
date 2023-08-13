# RUST-STEP_FUNCTION USING AWS LAMBDA

Building and Deploying Aws Rust Function Made using Rust

## Overview

This project implements an awesome algorithm for doing something very important. It showcases some of the cool features of Rust like:

- Blazing fast performance
- Memory safety without garbage collection
- Zero-cost abstractions

## Getting Started

### Prerequisites

- You'll need to have Rust installed on your system. You can install it from [https://rustup.rs](https://rustup.rs).
- .....................
- `~/.aws/credentials` here add your AWS Credentials **or** use vscode AWS TOOLKIT EXTENSION

### Installing

Clone the project and build it with Cargo:

```
git clone https://github.com/username/rust-step-function.git
cd rust-step-function
```

### Running

To run the program:
**Deploying Rust-Input Function**
```
cd rust-input
cargo lambda build --release
cargo lambda deploy rust-input --profile iamusername -r region
```
**Deploying Rust-Output Function**
```
cd rust-output
cargo lambda build --release
cargo lambda deploy rust-output --profile iamusername -r region
```

## Creating Step Function

- Go to Step Function
- Create a new state Machine
- Choose lambda and name the function input and assign **rust-input** to it
- Choose another lambda and name the function output and assign **rust-output** to it

# Using Step Function
- choose New Execution
- set json as {  "name":"Marco"  } and format json
- ![step](https://github.com/dewasahu2003/rust-step-function/assets/95997298/d6497869-0530-4213-ac8c-666f07111dc9)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Author

Dewa Sahu - [Website](https://portfolio-beryl-seven-13.vercel.app/) / [GitHub](https://github.com/dewasahu2003)
