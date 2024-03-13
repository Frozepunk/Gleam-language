# GLEAM

Gleam is a friendly language for building type-safe systems that scale.

## Introduction

This repository serves as a resource for learning the basics of the Gleam language. Here, you'll find explanations and examples to help you get started.

## Installation

To install Gleam, please follow the official installation guide available [here](https://gleam.run/getting-started/installing/).

Once installed, verify the installation by opening your terminal or command prompt and running the following command:

```bash
gleam --version
```

If the version number is displayed, it indicates a successful installation.

## Creating a Project

To create a new Gleam project, use the following command:

```bash
gleam new project-name
```

For example, to create a project named "hello", run:

```bash
gleam new hello
```

This will create a directory with the specified project name. Navigate to this directory and open it in your favorite code editor.

## Project Structure

- `gleam.toml`: Contains configuration settings for the project.
- `src/`: Directory for program source files.
- `test/`: Directory for additional code used in testing the project.

### Let's Get Started with Our First Program

Let's create the project using the following command:

```bash
gleam new hello
```
* Navigate into the "hello" directory, open your text editor, and within the "src" directory, you'll find a file named "hello.gleam". Inside this file, you'll see the following code:

```bash
import gleam/io

pub fn main() {
  io.println("Hello, world!")
}
```
* Open your terminal in that directory and run the following command:

```bash 
gleam run hello.gleam
```
* Congratulations! You have written your first program in Gleam. Now, let's understand what the above program does:

`import gleam/io`: This line imports the gleam/io module, which is part of the Gleam standard library. It provides functionality for input and output operations.

`pub fn main()`: Here, pub means public, fn means function, and main refers to the entry point of the program or the main function.

`io.println("Hello, world!")`: This line prints "Hello, world!" to the console.