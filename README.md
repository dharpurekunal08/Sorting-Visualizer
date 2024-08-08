# Sorting Visualizer

Sorting Visualizer is a C++ application that visually demonstrates different sorting algorithms using the SDL2 library. This tool helps in understanding the working of various sorting algorithms by visualizing the steps involved in sorting an array.

## Features

- **Visualization**: The application provides a visual representation of the sorting process, making it easier to understand how different algorithms work.
- **Algorithms Covered**:
  - Selection Sort
  - Insertion Sort
  - Bubble Sort
  - Merge Sort
  - Quick Sort
  - Heap Sort
- **Randomized Array**: You can generate a new randomized list of fixed size (130 elements) for sorting.
- **User Controls**: Simple keyboard controls to interact with the application and select different sorting algorithms.

## Installation

### Prerequisites

- **SDL2 Library**: Make sure you have SDL2 installed on your system. You can install it using the following command:

  - **Ubuntu**: `sudo apt-get install libsdl2-dev`
  - **Windows**: Download the SDL2 development library from [libsdl.org](https://libsdl.org/download-2.0.php) and follow the installation instructions.

- **C++ Compiler**: You need a C++ compiler like `g++` to compile the project.

### Compiling the Project

1. Clone the repository or download the source code.

2. Navigate to the project directory.

3. Compile the code using the following command:

    ```bash
    g++ -o sorting_visualizer sorting_visualizer.cpp -lSDL2
    ```

4. Run the executable:

    ```bash
    ./sorting_visualizer
    ```

## Usage

1. After starting the application, press `ENTER` to see the available controls.
2. Use the following keys to interact with the visualizer:

    - `0`: Generate a new randomized list.
    - `1`: Start Selection Sort.
    - `2`: Start Insertion Sort.
    - `3`: Start Bubble Sort.
    - `4`: Start Merge Sort.
    - `5`: Start Quick Sort.
    - `6`: Start Heap Sort.
    - `q`: Quit the application.

3. Watch the sorting algorithm in action as it visualizes the steps involved in sorting the array.


## How It Works

The application initializes an SDL2 window and renderer for graphical output. Different sorting algorithms are implemented in C++ and are called based on user input. As the array is being sorted, the visualizer updates the window to reflect the changes in the array, allowing you to see how the algorithm progresses.

