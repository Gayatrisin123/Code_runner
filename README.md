# 🧠 CodeRunner - Online Code Compiler & Executor

An online compiler and code runner that supports multiple programming languages such as C++, Python, Java, and JavaScript. Users can write code, provide input, and execute it in a secure sandboxed environment—all from a web browser.

## ✨ Features

- 📝 Syntax-highlighted code editor (powered by Monaco Editor)
- 🌍 Multi-language support: C++, Python, Java, JavaScript
- 📥 Custom input (stdin) support
- 🔐 Secure, sandboxed code execution using Docker
- ⚡ Real-time output display (stdout, stderr, execution time)
- 🧩 Scalable and modular architecture

---



## 🛠 Tech Stack

**Frontend:**
- React.js
- HTML, CSS, JavaScript
- Monaco Editor

**Backend:**
- Node.js
- Express.js
- Docker (for sandboxing code execution)
- child_process module

**Optional:**
- MongoDB (for storing code history or user data)

---

## 📦 Installation

### Prerequisites

- Node.js and npm
- Docker installed and running
- (Optional) MongoDB if using database features

### Clone the Repository

```bash
git clone https://github.com/your-username/code-runner.git
cd code-runner
