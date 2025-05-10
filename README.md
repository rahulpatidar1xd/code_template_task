# code_template_task
# Code Template API 🚀

An HTTP API that generates executable code skeletons (like LeetCode/HackerRank starter templates) for Data Structures & Algorithms (DSA) problems across multiple programming languages.

---

## 🌐 Supported Languages

- Python 3.12
- Java 17
- C++20
- JavaScript (Node.js 20)

---

## 📦 Features

- Generates idiomatic starter code based on function signatures.
- Hides all I/O and boilerplate — user can start coding immediately.
- Supports:
  - Multiple parameters (including nested/complex types)
  - Multiple return values
- Language-agnostic signature DSL (e.g., `int[]`, `List<string>`, `Tree<int>`)
- Input validation and meaningful error responses.

---

## 🚀 Quick Start

### 🔧 Prerequisites

- Python 3.10+ installed
- `git` installed

### 📁 Clone and Setup

```bash
git clone https://github.com/rahulpatidar1xd/code_template_task.git
cd code_template_task
python -m venv venv
venv\Scripts\activate   # On Windows
# OR
source venv/bin/activate  # On Mac/Linux

pip install -r requirements.txt
