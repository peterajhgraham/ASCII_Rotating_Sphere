# Rotating ASCII Cube

A C++ program that generates a rotating 3D cube using ASCII characters. It is designed with dynamic shading and realistic rotation based on concepts within linear algebra such as dot product, vector normalization, as well as the projection and rendering of 3D points onto a 2D screen.

*Enjoy the rotating cube*!

## Directory Structure

```
ASCII_Rotating_Cube/
├── rotating_cube.cpp
├── LICENSE
├── README.md
└── .gitignore
```

## Prerequisites

* **C++ Compiler**

* **Terminal** (Unix-like systems recommended)

## Usage

1. **Compile**:
   ```
   g++ -o rotating_cube rotating_cube.cpp -lm
   ```

2. **Run**:
   ```
   ./rotating_cube
   ```

## Customization

* **Rotation Speed:** You can modify the rotation speed by changing the values of `A += 0.04f;` and `B += 0.03f;` in the main loop

* **Cube Size:** Adjust the cube size by modifying the `cubeSize` variable

## Notes

* Best viewed in a terminal with at least 160x44 characters

* The code uses the Bresenham's line algorithm for drawing lines between the cube's vertices
