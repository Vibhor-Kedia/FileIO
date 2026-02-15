# FileIO
A lightweight C++ static library for basic file input/output operations (trust me - I know).
This project is built in Visual Studio and demonstrates simple read/write functionality.

---

## 📂 Project Structure
- `FILEIO.cpp` — Implementation of file I/O functions
- `FILEIO.h` — Header file with function declarations
- `FILEIO.sln` — Visual Studio solution
- `FILEIO.vcxproj` — Visual Studio project file

---

## ⚙️ Build Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Vibhor-Kedia/FileIO.git

2. Open FILEIO.sln in Visual Studio.
3. Build the project (Debug or Release)
4. The output will generate a FILEIO.lib which can be linked to other projects

## 🚀 Usage
``` Cpp
#include "FileIO.h"

int main() {
    FileIO::WriteToFile("test.txt", "Hello, world!");
    std::string content = FileIO::ReadFromFile("test.txt");
    std::cout << content << std::endl;
    return 0;
}
```
## 📜 License
This project is open source under the MIT License.
Feel free to use, modify, and share.
