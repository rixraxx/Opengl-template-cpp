# OpenGL-template for C++

This repository provides a simple template for setting up an OpenGL project in C++ using Visual Studio Code. It includes configuration files for building and debugging with MinGW on Windows.

## Folder Structure
```
opengl-template/
├── src/
│ └── main.cpp # Your main application file
| └── glfw3.dll # GLFW dynamic library
├── include/ # Include directory for header files
│ └── (header files if any)
├── lib/
│ └── other library files (.lib or .dll)
├── .vscode/ # VS Code configuration files
│ ├── launch.json
│ ├── tasks.json
│ └── c_cpp_properties.json
└── .gitignore # Git ignore file
```

## Getting Started

### Prerequisites

- [Visual Studio Code](https://code.visualstudio.com/)
- [MinGW](http://www.mingw.org/) or another GCC-compatible compiler
- [Git](https://git-scm.com/)

### Setup

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/opengl-template-cpp.git
    cd opengl-template-cpp
    ```

2. **Open the project in Visual Studio Code:**

    ```sh
    code .
    ```

3. **Install necessary extensions in VS Code:**
    - C/C++ (Microsoft)
    - CMake (Optional, if using CMake for project management)
    - Code Runner (Optional, for running code snippets)

### Building and Running

1. **Build the project:**
    - Press `Ctrl+Shift+B` to run the build task defined in `tasks.json`.

2. **Run the project:**
    - Press `F5` to start debugging with the configuration defined in `launch.json`.

### Configuration Files

- **`launch.json`:** Configures debugging settings.
- **`tasks.json`:** Defines build tasks.
- **`c_cpp_properties.json`:** Sets include paths and IntelliSense configurations.

### Additional Notes

- Ensure that the `glfw3.dll` and any other necessary DLLs are located in the `lib` directory or a directory included in your system's `PATH`.
- Modify the `tasks.json` and `c_cpp_properties.json` files according to your specific setup and dependencies.

## Contributing

Feel free to fork this repository and make your own modifications. Pull requests are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
