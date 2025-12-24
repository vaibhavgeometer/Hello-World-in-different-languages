# Hello World in Different Languages

This repository contains "Hello World" programs written in various programming languages. It serves as a simple reference for syntax differences across languages.

## Supported Languages

The following languages are currently included in the `Hello World` directory:

- **C**: `c.c`
- **C++**: `cpp.cpp`
- **C#**: `cs.cs`
- **Java**: `java.java`
- **JavaScript**: `js.js`
- **Python**: `py.py`

---

# How to Run the Programs

This guide provides detailed instructions on how to run the "Hello World" programs in various programming languages included in this repository.

## Table of Contents
1. [General Setup](#general-setup)
2. [Python](#python)
3. [JavaScript (Node.js)](#javascript)
4. [Java](#java)
5. [C](#c)
6. [C++](#c-plus-plus)
7. [C#](#c-sharp)

---

## 1. General Setup <a name="general-setup"></a>

1. **Open a Terminal**:
   - **Windows**: Press `Win + R`, type `cmd` or `powershell`, and press Enter.
   - **macOS/Linux**: Open the "Terminal" app.
2. **Navigate to the Directory**:
   Use the `cd` command to navigate to the `Hello World` folder where the files are located.
   ```bash
   cd "Hello World"
   ```

---

## 2. Python <a name="python"></a>

**Prerequisites**: [Python](https://www.python.org/) must be installed.
Check by running: `python --version` or `python3 --version`

**Command**:
```bash
python py.py
```
*(Note: On systems with both Python 2 and 3, you might need to use `python3 py.py`)*

---

## 3. JavaScript (Node.js) <a name="javascript"></a>

**Prerequisites**: [Node.js](https://nodejs.org/) must be installed.
Check by running: `node -v`

**Command**:
```bash
node js.js
```

---

## 4. Java <a name="java"></a>

**Prerequisites**: [JDK (Java Development Kit)](https://www.oracle.com/java/technologies/downloads/) must be installed.
Check by running: `javac -version` and `java -version`

**Commands**:
You can run it directly (Java 11+) or compile it first.

**Option A (Direct Run - recommended for single files)**:
```bash
java java.java
```

**Option B (Compile and Run)**:
```bash
javac java.java
java Java
```
*(Note: The class name is 'Java', which is case-sensitive)*

---

## 5. C <a name="c"></a>

**Prerequisites**: A C compiler like [GCC](https://gcc.gnu.org/) (MinGW for Windows) must be installed.
Check by running: `gcc --version`

**Commands**:
1. **Compile**: `gcc c.c -o c_program`
2. **Run**:
   - **Windows**: `c_program.exe`
   - **macOS/Linux**: `./c_program`

---

## 6. C++ <a name="c-plus-plus"></a>

**Prerequisites**: A C++ compiler like [G++](https://gcc.gnu.org/) must be installed.
Check by running: `g++ --version`

**Commands**:
1. **Compile**: `g++ cpp.cpp -o cpp_program`
2. **Run**:
   - **Windows**: `cpp_program.exe`
   - **macOS/Linux**: `./cpp_program`

---

## 7. C# <a name="c-sharp"></a>

**Prerequisites**: [.NET SDK](https://dotnet.microsoft.com/download) or a C# compiler like `csc` (included with Visual Studio or Build Tools).
Check by running: `csc /version` or `dotnet --version`

**Commands (using csc)**:
1. **Compile**: `csc cs.cs`
2. **Run**: `cs.exe`
*(Note: The C# program in this repo includes `Console.ReadLine()`, so it will wait for you to press Enter before closing.)*

---

## Troubleshooting
- **'Command not found'**: Ensure the language/compiler is installed and added to your system's `PATH`.
- **File not found**: Ensure you are inside the `Hello World` directory.
- **Permissions**: On macOS/Linux, you might need to give execution permission to compiled files: `chmod +x program_name`.