# Rubik's Cube Solver 🧩

A C++ implementation of a **Rubik’s Cube Solver** using **Korf’s IDA\*** search algorithm with pattern databases for efficient solving.  

---

## 🚀 Features
- Models a virtual **3×3 Rubik’s Cube**
- Efficient **bitboard-based cube representation**
- Solver implemented with **IDA\*** and pruning
- Uses **Pattern Databases (PDBs)** for fast heuristic lookup
- Modular structure (`Solver`, `Model`, `Databases`, `PatternDatabases`)

---

## 📂 Project Structure
.
├── main.cpp # Entry point
├── Solver/ # Solver logic
├── Model/ # Cube model classes
├── Databases/ # Precomputed databases
├── PatternDatabases/ # Pattern DBs
├── CMakeLists.txt # Build configuration
└── README.md # Project documentation

---

## ⚙️ Installation & Build

### Prerequisites
- C++17 or later
- [CMake](https://cmake.org/) (3.15+ recommended)
- A C++ compiler (GCC/Clang/MSVC)

### Build Instructions
```bash
# Clone the repository
git clone https://github.com/piyushkant08/Rubik-s-Cube-Solver.git
cd Rubik-s-Cube-Solver

# Create build directory
mkdir build && cd build

# Run CMake
cmake ..

# Compile
cmake --build .

Run the Solver
./RubiksCubeSolver

📖 How it Works

Represents the Rubik’s Cube in memory

Uses IDA* search with heuristics from Pattern Databases

Prunes unnecessary states for faster solving

Returns an optimal (or near-optimal) move sequence

📝 License

This project is licensed under the MIT License.
Feel free to use and modify!
