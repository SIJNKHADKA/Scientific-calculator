
Welcome to the Calculator Project!

To make this project work on your computer, follow these steps:

Step 1: Get the MinGW Compiler

Visit the MinGW website: https://osdn.net/projects/mingw/
Download the installer (mingw-get-setup.exe) from the "Downloads" section.
Run the installer and follow the instructions to finish the installation.
While installing, choose the C and C++ compilers.
Step 2: Get the raylib Library

Visit the raylib website: https://www.raylib.com/
Go to the "Download" section.
Choose the right version for your computer and download the raylib ZIP file.
Extract the ZIP file to a location on your computer.
Step 3: Compile and Run the Calculator

Open a terminal or command prompt.
Go to the folder where you saved the calculator project files.
Use this command to compile the project (replace "path_to_raylib" with your raylib folder):
c
Copy code
g++ -o calculator.exe calc.cpp -Ipath_to_raylib\include -Lpath_to_raylib\lib -lraylib -lopengl32 -lgdi32 -lwinmm -std=c++11
Or, if you're using C:\raylib\w64devkit, run w64devkit.exe and then run this command:
wasm
Copy code
g++ calc.cpp -lraylib -lopengl32 -lgdi32 -lwinmm -o calculator
Run the compiled calculator with this command:
Copy code
calculator.exe
Now, you should see the calculator app working!

Feel free to check out the source code, make changes, and use the calculator. If you have questions, refer to the README file or email us at insijanced2341@gmail.com.

Happy coding!