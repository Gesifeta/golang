
# 🧠 Go Learning Plan (12 Weeks)

> Based on *Learning Go: An Idiomatic Approach to Real-World Go Programming (2nd Ed)*

---

## 📅 Weekly Breakdown

### **Week 1: Go Basics & Setup**
**Topics:**
- Go environment setup
Go project is called a module. A module is not just source code. It is
also an exact specification of the dependencies of the code within the module. Every
module has a go.mod file in its root directory. Running go mod init creates this file
for you.

- Every golang starts with import package main and an entry point func main().
### Formating
- Go comes with predefined formating standard, and uses tab for indenting. 
- [ ] go fmt ./... used to format the entire module's spacing but cannot fix brace errors. It applies to all the files in the current directroy.

- Hello World
- Go tooling basics (Chapter 1)
- Predeclared types & declarations (Chapter 2)

**Practice:**
- Write simple programs using `var`, `const`, and short declarations
- Play with literals, booleans, and numeric types

**Project:**
- 🛠️ *“Go CLI Calculator”*: build a calculator that performs arithmetic operations using user input.

---

### **Week 2: Composite Types**
**Topics (Chapter 3):**
- Arrays, Slices
- Strings, Runes, Bytes
- Maps
- Structs

**Practice:**
- Manipulate slices and maps
- Write struct-based data models

**Project:**
- 🗂️ *“Contact Book”*: a command-line contact manager using structs, slices, and maps.

---

### **Week 3: Control Flow**
**Topics (Chapter 4):**
- Blocks & shadowing
- `if`, `for`, `switch`, `goto`
- Loop idioms, range loops, labels

**Practice:**
- Refactor control flow-heavy functions
- Implement different types of loops

**Project:**
- 🎲 *“Dice Game Simulator”*: simulate dice rolls and scoring rules using control flow.

---

### **Week 4: Functions**
**Topics (Chapter 5):**
- Declaring & calling functions
- Multiple return values
- Anonymous functions, closures
- `defer`, function as values

**Practice:**
- Implement utility functions with multiple returns
- Use closures to manage state

**Project:**
- 📐 *“Math Toolkit”*: a Go library of reusable math utilities demonstrating functions and closures.

---

### **Week 5: Pointers**
**Topics (Chapter 6):**
- Pointers and memory
- Mutable parameters
- Performance implications

**Practice:**
- Refactor functions to use pointers
- Benchmark pointer vs value operations

**Project:**
- 🧮 *“Stats Tracker”*: collect and update metrics (average, sum) with pointer-based structs.

---

### **Week 6: Methods & Interfaces**
**Topics (Chapter 7):**
- Methods on types
- Interfaces & composition
- Embedding and polymorphism

**Practice:**
- Create interfaces and use them to generalize behavior
- Test polymorphic function calls

**Project:**
- 🧱 *“Shape Area Calculator”*: define interfaces for shapes and calculate areas using polymorphism.

---

### **Week 7: Generics**
**Topics (Chapter 8):**
- Generic functions & types
- Type constraints
- Comparable, type inference

**Practice:**
- Write type-safe utilities using generics
- Refactor previous code to use generics

**Project:**
- 🧰 *“Generic Utilities Library”*: create reusable data utilities with generics (e.g., reverse, map, filter).

---

### **Week 8: Errors**
**Topics (Chapter 9):**
- Error values, wrapping
- `errors.Is`, `errors.As`
- `panic`, `recover`

**Practice:**
- Build custom error types
- Wrap and unwrap errors with context

**Project:**
- 🕵️ *“User Auth CLI”*: simulate login/signup with custom errors and error wrapping for invalid input.

---

### **Week 9: Modules & Packages**
**Topics (Chapter 10):**
- `go.mod`, modules
- Creating packages
- Importing and documenting

**Practice:**
- Create and import custom packages
- Structure code across packages

**Project:**
- 📦 *“Modular Notes App”*: break a note-taking CLI into packages (`storage`, `ui`, `logic`).

---

### **Week 10: Tooling & Testing**
**Topics (Chapters 11 & 15):**
- `go run`, `go install`, `go test`
- Linting, govulncheck
- Unit tests, table tests, benchmarks

**Practice:**
- Add tests to your previous projects
- Use `go-cmp`, coverage, benchmarks

**Project:**
- 🔍 *“Test-Driven Library”*: create a small Go lib (e.g., string utilities) with full test coverage and benchmarks.

---

### **Week 11: Concurrency**
**Topics (Chapter 12):**
- Goroutines
- Channels
- `select`, `context`, WaitGroups

**Practice:**
- Implement goroutine coordination
- Use channels for communication

**Project:**
- 🔄 *“Concurrent Web Pinger”*: ping multiple websites concurrently and report response times.

---

### **Week 12: Advanced Go**
**Topics:**
- 📚 Standard Library (Chapter 13)
- 🧠 Context (Chapter 14)
- 🧪 Reflect, Unsafe, Cgo (Chapter 16)

**Practice:**
- Use `net/http`, `encoding/json`
- Explore `context.WithTimeout`
- (Optional) play with `reflect` for custom serialization

**Final Project:**
- 🚀 *“Go REST API Server”*: a fully concurrent API server with:
  - CRUD endpoints
  - JSON serialization
  - Context for request cancellation
  - Middleware with interfaces

---

## 📌 Tips for Success
- ✅ Do the exercises at the end of each chapter.
- 🧪 Write tests as you go (from Week 5 onward).
- 📚 Maintain a dev diary using Markdown to log progress.
- 🔄 Revisit/refactor earlier projects with new concepts (e.g., generics, interfaces).
