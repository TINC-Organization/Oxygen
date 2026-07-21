# Frequently Asked Questions (FAQ)

### 1. What is Oxygen?
Oxygen is a low-latency execution runtime engine designed to optimize low-level system execution and memory management for performance-critical applications.

---

### 2. Why use custom Arena Allocators instead of standard `malloc` or `new`?
Standard dynamic memory allocation can cause memory fragmentation and unpredictable latencies during continuous execution. Oxygen uses custom memory arenas to allocate large contiguous memory blocks upfront, providing near-instantaneous slicing and predictable performance.

---

### 3. Is Oxygen ready for production environments?
Oxygen is currently in active pre-release development (`v0.x`). While core memory structures and drivers are functional, APIs are subject to change before the stable `1.0.0` release.

---

### 4. How can I run Oxygen on Windows?
Oxygen includes multi-platform build triggers. Simply clone the repository and run the `Src/all.bat` script in your Command Prompt or PowerShell environment.

---

### 5. Who maintains Oxygen?
Oxygen is developed and maintained by **TINC Organization** alongside open-source community contributors.
