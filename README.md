# 🌍 Hello World in Different Languages

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg)
![Languages](https://img.shields.io/badge/Languages-6+-blue.svg)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-blue.svg)

A curated collection of **"Hello World"** programs across various programming languages. This repository is designed as a foundational reference for developers to explore basic syntax, boilerplate code, and execution steps across different environments.

---

## 📂 Repository Structure

Each language is organized into its own directory containing the source code and any necessary configuration files.

| Language | Directory | Primary File |
| :--- | :--- | :--- |
| 🐍 **Python** | [`./Python`](./Python) | `py.py` |
| 🟨 **JavaScript** | [`./JavaScript`](./JavaScript) | `js.js` |
| ☕ **Java** | [`./Java`](./Java) | `java.java` |
| 🔷 **C** | [`./C`](./C) | `c.c` |
| 💠 **C++** | [`./Cpp`](./Cpp) | `cpp.cpp` |
| 🎯 **C# (.NET)** | [`./Csharp`](./Csharp) | `cs.cs` |

---

## 🚀 Getting Started

Follow these instructions to run the programs on your local machine.

### 📋 Prerequisites

Ensure you have the following installed:

- **Python 3.x**: [python.org](https://www.python.org/)
- **Node.js**: [nodejs.org](https://nodejs.org/)
- **JDK 11+**: [adoptium.net](https://adoptium.net/)
- **GCC / G++**: [gcc.gnu.org](https://gcc.gnu.org/)
- **.NET SDK**: [dotnet.microsoft.com](https://dotnet.microsoft.com/)

### 💻 Execution Guide

#### 🐍 Python
```bash
cd Python
python py.py
```

#### 🟨 JavaScript (Node.js)
```bash
cd JavaScript
node js.js
```

#### ☕ Java
```bash
cd Java
# Option A: Direct Run (JDK 11+)
java java.java

# Option B: Compile and Run
javac java.java
java Java
```

#### 🔷 C
```bash
cd C
gcc c.c -o c_program
./c_program  # Windows: .\c_program.exe
```

#### 💠 C++
```bash
cd Cpp
g++ cpp.cpp -o cpp_program
./cpp_program  # Windows: .\cpp_program.exe
```

#### 🎯 C# (.NET)
```bash
cd Csharp
dotnet run
```

*Alternatively, using the C# compiler (`csc`):*
```bash
csc cs.cs
.\cs.exe
```

---

## 🛠️ Troubleshooting

- **Command Not Found**: Ensure the compiler/runtime is added to your system's `PATH`.
- **Permissions**: On Linux/macOS, use `chmod +x <binary>` if execution is denied.
- **SDK Versions**: Some languages (like C#) require specific SDKs to build project files.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. **Fork** the Project
2. **Create** your Feature Branch (`git checkout -b feature/AddLanguage`)
3. **Commit** your Changes (`git commit -m 'Add [Language] Hello World'`)
4. **Push** to the Branch (`git push origin feature/AddLanguage`)
5. **Open** a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">Made with ❤️ for the Developer Community</p>
