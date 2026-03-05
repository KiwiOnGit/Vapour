# Vapour
a game engine written in, C, C++ and python that was made for my personal game but can be modified into any other projects.

# Project Title

Vapour, a custom engine built in C, C++, and Python 3 that is made to be similar lightweight, easily moddable and comparable in someways to the source engine.

## Table of Contents

*   [Description](#description)
*   [Installation](#installation)
*   [Usage](#usage)
*   [Contributing](#contributing)
*   [License](#license)

## Description
Vapour is a personal project that i have started working on, and it's currently in its infancy with almost nothing added/implemented, but that's soonly changing as I'll be committing to this. I made it open source so that anybody who wants to use it can freely. the engine and the game are going to be the same thing under the hood, think of the under the hood engine like this, the engine and the game are tightly interwined, the same at that. currently its only opengl but vulkan support will be after i get stable fast renderering with opengl.


# Roadmap


## Roadmap Phases!

### Phase 1: Foundation (Current)
Status: Infancy / Pre-Alpha
Core engine implementation in C and C++.
Basic Python 3 scripting integration.
Stable OpenGL rendering pipeline.
"Boring stuff first" architecture strategy. 



### Phase 2: Next Gen Rendering
Status: Planned
Implementation of Vulkan API support.
Migration from experimental to stable rendering. 
advanced input, more than just keyboard/mouse button clicks
early level editor
3d model, audio and video support
basic physics system
gui system



### Phase 3: Production Tools
Status: Future 
Game export and compilation tools.
Visual Studio and Rider IDE support.
Full "fun stuff" feature set (Asset management, Level editor). 
improve early phase 2 stuff



## Installation

Instructions for installing vapour,

*   **Prerequisites:**
    *   You need GCC for the C parts of the engine.
    *   you need G++ for the C++ parts of the engine.
    *   You need Python3 for the Python parts of the engine.
    *   You need Glew and GLFW if using the opengl renderer
*   **Steps:**
    1. simply fork the engine and place it someplace nice.
    2. Use a compatible IDE, currently that would be vscode. -im planning rider and visual studio support but for now its just vscode.
    3. Open the projects root folder in your compatible IDE.

### Commands:
Macos: - for mac you need to install homebrew, macports also works too.

      brew install glew glfw

      
Linux: - for linux you also need homebrew, or your pkg manager

      brew install glew glfw

      
Windows:
      Downloads are here: 
      
      https://www.glfw.org/download
      
      https://glew.sourceforge.net/

## Usage

compiling the engine and exporting software/games are not currently supported, since this project is very new (yes that new) its simply setting the footwork of what will be available. meaning boring stuff first fun stuff later. and compiling and exporting and apart of the fun stuff. that said once the engine has a lot of core components and functionality i will update this.

## Contributing

Welcome to Vapour! We're excited that you want to contribute.

Reporting Bugs: Create a new GitHub issue with clear steps to reproduce, expected behavior, and actual behavior.  
Proposing Changes/Features: Open an issue first to discuss major changes or enhancements before starting work.  
Code Contributions: Fix bugs, add features, or optimize performance.  
Documentation: Improve our guides, tutorials, or README files.

Fork the Vapour repository to your GitHub account.  
Clone your fork to your local machine.  
Set up your environment: Follow the README.md instructions to install dependencies and ensure the project runs correctly before making changes. Vapour uses C, C++, and Python.  
Create a branch: <mark>git checkout -b Vapour</mark>  
Do note that you can change the name of your branch from vapour to anything, maybe try <mark>git checkout -b Cheesepuffs</mark>

# License 

This project is licensed under the terms of the **MIT License**.

You should have received a copy of the MIT License along with this program.

***

## A Note on Licensing:
some third party made dependencies of the vapour engine may not use the same license, for ease of knowing them i'll do my best to add said code and components here.

### Third-Party Components:


**GLEW (The OpenGL Extension Wrangler Library): The GLEW source code is licensed under the Modified BSD License, the Mesa 3-D License (MIT), and the Khronos License (MIT) [1.1.1][1.1.2].**


**OpenGL: This project utilizes the OpenGL® Specification provided by the Khronos Group. OpenGL is a registered trademark of Hewlett Packard Enterprise.**


**GLFW (Graphics Library Framework): The GLFW source code is licensed under the permissive zlib/libpng license, a BSD-like license that permits use in commercial applications and static linking with closed source software.**

# MIT License

Copyright (c) 2026 Ely Wright

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
