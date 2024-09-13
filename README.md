# File Copy Program in C

## Overview
This project contains C programs that implement file copying functionality. The programs are designed to copy the contents of one file to another, handling basic file I/O operations. The project includes multiple variations of the file copy program to demonstrate different approaches to file copying in C.

## Features
- **File Copy**: Copies the contents of a source file to a destination file.
- **Error Handling**: Handles basic errors such as file not found or insufficient permissions.
- **Multiple Implementations**: The project contains different implementations for copying files across multiple C files (`copy.c`, `copy1.c`, `copy2.c`).

## Project Structure
- **`copy.c`**: The basic file copy implementation.
- **`copy1.c`**: A variation of the file copy implementation.
- **`copy2.c`**: Another variation of the file copy program.

## How to Compile and Run

### Prerequisites
- **C Compiler**: Ensure you have a C compiler such as `gcc` installed.

### Building the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/arnold-shakirov/Copy-File-Problem.git
    ```

2. Navigate to the project directory:


3. Compile any of the C files:
    ```bash
    gcc -o copy copy.c
    gcc -o copy1 copy1.c
    gcc -o copy2 copy2.c
    ```

### Running the Programs
Once compiled, run the programs with the following commands:

- For `copy.c`:
    ```bash
    ./copy source_file destination_file
    ```

- For `copy1.c`:
    ```bash
    ./copy1 source_file destination_file
    ```

- For `copy2.c`:
    ```bash
    ./copy2 source_file destination_file
    ```

Replace `source_file` with the file you want to copy and `destination_file` with the name of the file you want to create.

## Requirements
- **C Compiler**: GCC or any other standard C compiler.

## Installation
1. Clone or download the repository.
2. Compile the C programs using `gcc` or any other standard C compiler:
    ```bash
    gcc -o copy copy.c
    ```

3. Run the program:
    ```bash
    ./copy source_file destination_file
    ```
    
## Contact
For any questions or suggestions, feel free to reach out to me at [ashakirov@stetson.edu].
