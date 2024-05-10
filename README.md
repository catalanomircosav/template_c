# Template C Project

![C Programming](https://cdn.pixabay.com/photo/2017/08/10/12/44/code-2620118_960_720.jpg)

This project is a simple template to start working on C language projects using Visual Studio Code as the development environment. The template includes configurations for compiling and running C projects, along with a basic folder structure.

## Folder Structure

The project has the following folder structure:
- root
  - build
    - build.exe
  - src
    - file1.c
    - file2.c
    - ...
  - include
    - file1.h
    - file2.h
    - ...
  - main.c

- **build**: This folder will contain the executable of the project after compilation.
- **src**: Contains all the `.c` source files except the main file `main.c`.
- **include**: Contains all the `.h` header files.
- **main.c**: The main source file of the project.

## Configuration

### tasks.json

The `tasks.json` file is configured to compile the project using the `gcc` compiler. The task configuration ensures that the `.c` source files are compiled together with the `main.c` file, producing an executable inside the `build` folder.

### launch.json

The `launch.json` file is configured to run the produced executable after compilation. It's set to start debugging the program.

## Instructions

1. **Clone** this repository to your local machine.
2. Make sure you have **gcc** and **Visual Studio Code** installed.
3. **Open** the project in Visual Studio Code.
4. **Modify** the `.c` source files according to your needs.
5. **Compile** the project using the build task (`Ctrl + Shift + B`).
6. **Run** the program by pressing `F5` or using the debug task.

## Examples

In the `src` folder, you will find some example files as a starting point for your project.

## Contributing

If you find bugs or have suggestions to improve this template, feel free to open a new issue or send a pull request.
