# Vulkan Test
This repository contains a Vulkan test project developed by Hloha. It serves as a simple demonstration of Vulkan's capabilities and can be used as a starting point for Vulkan-based projects.

## Table of Contents
Introduction
Features
Installation
Usage
Contributing
License

## Introduction
Vulkan Test is a project that showcases the usage of the Vulkan API, which is a low-level graphics and compute API. It demonstrates the basic setup required to create a Vulkan application, including the initialization of the Vulkan instance, device, and swap chain. The project includes various rendering techniques, such as vertex and index buffers, shaders, and pipeline creation.

## Features
Vulkan instance creation and initialization
Device selection and initialization
Swap chain creation and image presentation
Vertex and index buffer creation
Shader compilation and pipeline creation
Basic rendering techniques
Error handling and validation layers

## Installation
To run the Vulkan Test project, follow these steps:

1.Clone the repository to your local machine using Git:

```bash
git clone https://github.com/Hloha/Vulkan-test.git
```
1.Install the necessary dependencies:
Vulkan SDK: Ensure you have the Vulkan SDK installed on your system. You can download it from the official Vulkan website (https://www.vulkan.org/sdk).
CMake: Make sure CMake is installed on your machine. You can download it from the CMake website (https://cmake.org/download).
2.Build the project:

Open a terminal or command prompt and navigate to the project directory.
Create a build directory:
bash
Copy code
mkdir build
cd build
Generate the build files using CMake:
Copy code
cmake ..
Build the project:
css
Copy code
cmake --build .
1.Run the application:
• After a successful build, you should find the executable in the build directory.
• Execute the application to see the Vulkan test in action.

## Usage
Once the Vulkan Test project is built and running, you can explore its features and capabilities. The application should open a window and display a simple rendering using Vulkan.

Use the following controls to interact with the application:

W, A, S, D: Move the camera in the scene.
Left Mouse Button: Rotate the camera.
Feel free to modify the code and experiment with different rendering techniques to further explore Vulkan's capabilities.

## Contributing
Contributions to Vulkan Test are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. Follow these guidelines when contributing:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and test them thoroughly.
Commit your changes with clear and descriptive commit messages.
Push your branch to your forked repository.
Open a pull request, describing your changes and the problem they solve.

## License
This project is licensed under the MIT License. Feel free to use and modify the code according to the terms of the license.
