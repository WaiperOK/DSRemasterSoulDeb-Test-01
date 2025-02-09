# DSRemasterSoulDeb-Test-01

This project provides a manual memory injector and a DLL-based debug menu designed for modifying in-game parameters (such as souls) in Dark Souls: Remastered.

## Features
- Manual Memory Injection: Users can manually input memory addresses and the number of souls to inject using an intuitive interface.
- Dynamic DLL Debug Menu: The injected DLL activates a debug menu within the game, allowing for real-time modification of game parameters.
- Safety Checks: Integrated input validation and memory protection checks ensure stability.

### Core Components
1. DLL Injection Logic:
   - `dllmain.cpp`: Initializes the debug menu and starts the memory management threads.
   - `MemoryManager.cpp`: Handles direct memory writing to specific game addresses.


