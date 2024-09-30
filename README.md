<h1 align="center">Smart-Traffic-management-simulation</h1>

<div align="center">

[![Python version](https://img.shields.io/badge/python-3.10.11-blue.svg)](https://www.python.org/downloads/release/python-370/)
[![License: Apache 2](https://img.shields.io/badge/License-Apache-yellow.svg)](https://www.apache.org/licenses/LICENSE-2.0)

<h4>This Smart-Traffic-management-system uses live images from the cameras at traffic junctions for traffic density calculation and sets the signal timers accordingly, thus reducing the traffic congestion on roads, providing faster transit to people, and reducing fuel consumption.</h4>
</div>
<div align="center">
    <h2>Simulation helps to show how traffic can be managed by using switching algorithm</h2>
</div>


### These are the description of libraries used in this Simulation:- 

* `Random` - The random library lets you select a random element from a sequence, whether it's a list, a string, or any iterable.
    
* `Math` - This part of the mathematical library is designed to work with numbers and their representations. It allows you to effectively carry out the necessary transformations with support for NaN (not a number) and infinity and is one of the most important sections of the Python math library. Below is a short list of features for Python 3rd version.
  
    * `math.ceil(x)` - return the ceiling of x, the smallest integer greater than or equal to x
  
    * `math.comb(n, k)` - return the number of ways to choose k items from n items without repetition and without order.
  
* `Time` -  Times in pygame are represented in milliseconds (1/1000 seconds). Most platforms have a limited time resolution of around 10 milliseconds.
    
* `Threading` -  In the context of Python, threading is a built-in module that allows various threads to execute concurrently.
    Threads run in the same unique memory heap. That way, each thread can access every variable and data structure of the program. While they do share the same heap space, each thread has its own stack
    		t = threading.Thread(target=hello_world)
    		t.start().
    
* `PyGame`  -   Pygame provides functions for creating programs with a graphical user interface, or GUI
* `SYS`  - The sys module provides functions and variables used to manipulate different parts of the Python runtime environment.
* `OS`   -	Python OS module provides the facility to establish the interaction between the user and the operating system.
-----------------------------------------------------------------------------------------------------------------

### About the environment of PyGame

Pygame simulations work on a wide variety of environments, as Pygame is a cross-platform library. Here are the main environments where it functions smoothly:
1. `Operating Systems`
    * Windows: Any modern version of Windows (Windows 10, 11, etc.)
    * Linux: Popular distributions like Ubuntu, Fedora, Arch Linux, etc.
    * macOS: Pygame works on macOS, though some additional steps may be needed for installation.
2. `Python Versions`
   *	Pygame supports Python 3.10.11 (recommended).
3. `Dependencies`
   *    Pygame requires SDL (Simple DirectMedia Layer), a cross-platform library that handles multimedia, input devices, and window management. When installing Pygame, the necessary SDL libraries are usually included.
4. `Development Environment`
      *	Pygame can run on various Python IDEs, such as:
        *	IDLE (the default Python IDE)
        *	PyCharm
        *	VS Code (with Python extensions)
        *	Jupyter Notebooks (though less common for real-time simulation)
5. `Hardware Requirements`
      *	Pygame simulations are not resource-intensive and can run on machines with basic hardware, but performance may vary depending on the complexity of the simulation. It works well with standard graphics and audio hardware available in most consumer laptops and desktops.
----------------------------------------------------------------------------------

### Cross-plateform libraries

A cross-platform library is a software library designed to work on multiple operating systems and environments without requiring significant changes to the code. The goal of such a library is to allow developers to write code once and deploy it across various platforms (like Windows, macOS, Linux, Android, etc.) with minimal adjustments. This saves time and effort, as the same core functionality can be reused across different environments.

--------------------------------------------------------------------------------------

### Key Features of Cross-Platform Libraries

  1.	Platform Independence: They abstract away the underlying platform-specific details, so the developer doesn’t need to worry about how the operating system manages low-level tasks like file access, graphics rendering, or input handling.
  2.	Unified APIs: Cross-platform libraries typically provide a consistent Application Programming Interface (API) that works the same on all supported platforms. This means the same function calls can be used across different environments.
  3.	Broad Compatibility: These libraries often support a range of devices, from desktop computers to mobile phones, and sometimes even embedded systems.

----------------------------

### Prerequisites

*    Python 3.10.11
*    Understanding of co-ordinates in screen.
  
---------------------------

### Installation

Step 1: Install required pakages on terminal

    `pip install -r requirements.txt`
    
    `python setup.py build_ext --inplace`
    
Step 2: To run the code

    `python simulation.py`
