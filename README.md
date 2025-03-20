# Image Randomizer

## **About this Project**
This project generates random images based on the height and width given by the user.

### **Instructions for downloading dependencies**  

Before building, ensure you have the required dependencies installed:  

#### **Linux:**  
```bash
sudo apt install cmake libpng-dev
```

#### **MacOS**
```bash
brew install cmake libpng
```
---

## **Instructions for formatting**

The code will already be formatted when you download the repo but to reformat it just run:
```bash
clang-format --style=Google <filename>
```

## **Instructions for building**  

Use `cmake` to build:  

```bash
mkdir build && cd build
cmake ..
make
```
---

## **Instructions for running**  
**MAKE SURE YOU ARE IN THE BUILD DIRECTORY BEFORE RUNNING THESE COMMANDS!**

Run this command to generate the random image:
```bash
./RandomImage <filename> <width> <height>
```