# Atom-Simulation

Atom Simulation (OpenGL Mini Project)
This project is a simple Atom simulation implemented in C using OpenGL (GLUT) .
It visually represents the atomic structure of elements from Hydrogen (Z=1) up to Neon (Z=10) by simulating orbits and electron movement around the nucleus.

📌 Features
* Interactive simulation of atoms with orbiting electrons.
* Supports elements: Hydrogen , Helium , Lithium , Beryllium , Boron , Carbon , Nitrogen , Oxygen , Fluorine , Neon .

* Right-click context menu:
 - Select element
 - Start/Stop simulation
 - Go to home screen
 - Exit
  
* Keyboard controls:
 - Enter → Go to main simulation screen
 - Spacebar → Resume rotation
 - S → Stop rotation
 - Q → Quit program
 - Esc → Resize window (700×700)
 - F10 → Toggle Fullscreen
  
🖥️ Requirements
OpenGL
 - GLUT (OpenGL Utility Toolkit)
 - C/C++ compiler (e.g., GCC)
   
On Ubuntu/Debian-based systems, install with:
sudo apt-get install freeglut3-dev

 On Windows, you can use:
   - Code::Blocks with GLUT
   - Visual Studio with OpenGL configured
   - MinGW with freeglut

🚀 Compilation & Execution
  - Linux / macOS:
    gcc main.cpp -lGL -lGLU -lglut -lm -o atom_simulation
   ./atom_simulation

Windows (MinGW):
g++ main.cpp -lfreeglut -lopengl32 -lglu32 -o atom_simulation.exe
atom_simulation.exe

🎮 Usage
     - Run the program.
     - Press Enter to go from the home screen to the simulation screen.
     - Right-click to open the menu and select an element.
     - Left-click to start animation.
     - Use keyboard/mouse controls to interact with the simulation.

📜 License :
        This project is for educational purposes (mini-project). You are free to modify and use it for learning.
    
        Would you like me to also create the actual `README.md` file and save it alongside your `main.cpp` so you can directly push it to GitHub .
