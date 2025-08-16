# 🌌 Simple 3D Raytracer

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

---

## 🛠 Requirements
- A C++ compiler (g++, clang++, or MSVC)
- Works on **Linux, macOS, and Windows**
- (Optional) [ImageMagick](https://imagemagick.org) for converting `.ppm` → `.png`

---

## 🚀 Build & Run

// [compile]
// On Linux/macOS (any compiler):
//   c++ -O3 -Wall -o raytracer raytracer.cpp
//   clang++ -O3 -Wall -o raytracer raytracer.cpp
//   g++ -O3 -Wall -o raytracer raytracer.cpp
//
// On Windows (MinGW):
//   g++ -O3 -Wall -o raytracer.exe raytracer.cpp
//   raytracer.exe
//
// Convert .ppm to .png (optional):
//   magick untitled2.ppm untitled2.png
// [/compile]


🖼 Output & Conversion

After running, the program generates:

untitled2.ppm

You can:

Open .ppm with GIMP, IrfanView, Photoshop, or

Convert it to PNG/JPG using ImageMagick:
bash
magick untitled2.ppm untitled2.png

📖 Credits

This project is adapted from the tutorial and source code by Scratchapixel:
👉 Introduction to Ray Tracing

Original code © 2012 Scratchapixel.com, distributed under the GNU General Public License v3.0.
I modified it for learning purposes (Windows compatibility, file handling, and experimenting with rendering).

---

⚡ This version:
- Adds **clear compile/run instructions**
- Explains `.ppm` → `.png` conversion
- Keeps things clean and professional  

Do you want me to also **add a small “Quick Compile Guide” block at the top of your repo** (like in the `.cpp` comments) so GitHub shows it immediately when people land on your repo?
