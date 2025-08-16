# Simple 3D Raytracer

A basic **raytracer written in C++** that renders simple 3D spheres with reflections, transparency, and lighting.  
The output is generated as a `.ppm` image, which can also be converted to `.png` for easier viewing.

---

## ✨ Features
- Ray-sphere intersection
- Diffuse shading
- Reflection and refraction
- Simple lighting model
- Outputs result as `untitled2.ppm`

---

## 📸 Sample Output

Here is a rendered image from the raytracer:

![Raytracer Output](untitled2.png)



## 🛠 Requirements
- C++ compiler (g++, clang++, or MSVC)
- Works on **Linux, macOS, and Windows**

---

## 🚀 Build & Run

### Windows (MinGW / g++)
g++ -O3 -o raytracer.exe raytracer.cpp
raytracer.exe

### Linux / macOS
bash
g++ -O3 -o raytracer raytracer.cpp
./raytracer

After running, the program generates:
untitled2.ppm
You can open .ppm with GIMP, IrfanView, Photoshop, or convert it to PNG/JPG.
Here’s an example render (converted to PNG):

📖 Credits

This project is adapted from the tutorial and source code by Scratchapixel:
Introduction to Ray Tracing

Original code is © 2012 Scratchapixel.com, distributed under the GNU General Public License v3.0.
I modified it for learning purposes (Windows compatibility, file handling, and experimenting with rendering).


