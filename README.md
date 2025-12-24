# Hello World in Different Languages

A collection of "Hello World" programs across various programming languages, organized for easy reference and testing. This repository serves as a simple guide to basic syntax and execution steps for different environments.

## 📁 Repository Structure

Each language has its own dedicated directory containing the source code and any necessary project files:

- **[C](./C)**: `c.c`
- **[C++](./C++)**: `cpp.cpp`
- **[C#](./C-Sharp)**: `Program.cs` (.NET Project)
- **[Java](./Java)**: `java.java`
- **[JavaScript](./JavaScript)**: `js.js`
- **[Python](./Python)**: `py.py`

---

## 🚀 How to Run

Follow the instructions below to run the programs on your local machine.

### 📋 General Setup

1. **Open a Terminal**:
   - **Windows**: Press `Win + R`, type `cmd` or `powershell`, and press Enter.
   - **macOS/Linux**: Open the "Terminal" app.

2. **Navigate to the Repository**:

   ```bash
   cd Hello-World-in-different-languages
   ```

---

### 🐍 Python

**Prerequisite**: [Python 3.x](https://www.python.org/)

```bash
cd Python
python py.py
```

### 🟨 JavaScript (Node.js)

**Prerequisite**: [Node.js](https://nodejs.org/)

```bash
cd JavaScript
node js.js
```

### ☕ Java

**Prerequisite**: [JDK 11+](https://www.oracle.com/java/technologies/downloads/)

```bash
cd Java

# Option A: Direct Run
java java.java

# Option B: Compile and Run
javac java.java
java Java
```

### 🔷 C

**Prerequisite**: A C compiler like [GCC](https://gcc.gnu.org/)

```bash
cd C
gcc c.c -o c_program
./c_program  # Use c_program.exe on Windows
```

### 💠 C++

**Prerequisite**: A C++ compiler like [G++](https://gcc.gnu.org/)

```bash
cd C++
g++ cpp.cpp -o cpp_program
./cpp_program  # Use cpp_program.exe on Windows
```

### 🎯 C# (.NET)

**Prerequisite**: [.NET SDK](https://dotnet.microsoft.com/download)

```bash
cd C-Sharp
dotnet run
```

*Alternatively, using the C# compiler (`csc`):*

```bash
csc Program.cs
Program.exe
```

---

## 🛠️ Troubleshooting

- **Command Not Found**: Ensure the relevant language runtime or compiler is installed and added to your system's `PATH`.
- **Permissions**: On macOS/Linux, you may need to grant execution permissions: `chmod +x <program_name>`.
- **Version Issues**: Some scripts might require specific versions (e.g., Python 3 vs Python 2).

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
