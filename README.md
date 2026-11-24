# Object-Oriented Programming (OOP) in C++

A comprehensive, clean, and compilable reference repository demonstrating all core and advanced concepts of Object-Oriented Programming in C++ (C++11/14/17/20).

---

## 📚 Topics Covered

| File | Topic | Key Concepts |
| :--- | :--- | :--- |
| **`01_classes_and_objects.cpp`** | Classes & Objects | Class definition, member functions, access specifiers (`public`, `private`), stack vs heap allocation (`new`/`delete`), `this` pointer, scope resolution `::`. |
| **`02_constructors_and_destructors.cpp`** | Lifecycle Management | Default, parameterized, copy (deep copy), and move constructors (`std::move`), member initializer lists, destructors, order of creation/destruction. |
| **`03_encapsulation_and_abstraction.cpp`** | Encapsulation & Abstraction | Data hiding, getters & setters with validation logic, public interfaces vs private internal logic. |
| **`04_inheritance.cpp`** | Inheritance Types | Single, multilevel, and multiple inheritance, resolving the diamond problem using `virtual` base classes, constructor order in hierarchies. |
| **`05_polymorphism_compile_time.cpp`** | Compile-Time Polymorphism | Static polymorphism: function overloading and operator overloading (unary `++`, binary `+`, stream insertion/extraction `<<`, `>>`). |
| **`06_polymorphism_run_time.cpp`** | Run-Time Polymorphism | Dynamic binding: `virtual` functions, abstract classes, pure virtual functions (`= 0`), virtual destructors, dynamic memory management via smart pointers (`std::unique_ptr`), downcasting with `dynamic_cast`. |
| **`07_friend_functions_and_classes.cpp`** | Friend Mechanism | `friend` functions and `friend` classes accessing private/protected members safely. |
| **`08_static_and_const_members.cpp`** | Static & Const Semantics | Static data members & static methods, `const` member functions, `const` objects, and the `mutable` keyword. |
| **`09_templates_and_generic_oop.cpp`** | Generic Programming | Class templates, member function templates, template specialization. |
| **`10_exception_handling_in_oop.cpp`** | Exceptions & RAII | Custom exceptions inheriting from `std::exception`, RAII (Resource Acquisition Is Initialization), exception-safe stack unwinding. |

---

## 🚀 How to Compile and Run

Make sure you have a modern C++ compiler (`g++` or `clang++` supporting C++17 or newer).

### Compile an individual file:
```bash
g++ -std=c++17 01_classes_and_objects.cpp -o 01_classes_and_objects
./01_classes_and_objects
```

### Compile all files at once:
```bash
for file in *.cpp; do
    g++ -std=c++17 "$file" -o "${file%.cpp}"
done
```

---

## 👤 Author
- **labib-4** (<labib.cse.cu@gmail.com>)
