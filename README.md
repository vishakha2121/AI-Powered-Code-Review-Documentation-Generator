# 🚀 AI-Powered Code Review & Documentation Generator

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![FastAPI](https://img.shields.io/badge/FastAPI-0.104.1-green.svg)
![React](https://img.shields.io/badge/React-18.2.0-blue.svg)
![Gemini](https://img.shields.io/badge/Gemini-AI-orange.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

> An intelligent platform that automatically reviews code, generates comprehensive documentation, and provides refactoring suggestions using AI.

---

## 📋 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Configuration](#-configuration)
- [Usage](#-usage)
- [API Documentation](#-api-documentation)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 📖 Overview

The **AI-Powered Code Review & Documentation Generator** is a comprehensive platform that leverages Google's Gemini AI to analyze code repositories, provide intelligent feedback, generate documentation, and visualize code architecture. It's designed to help developers maintain code quality, improve documentation, and streamline the code review process.

### Why This Project?
- 🎯 **Automated Code Review** - Save hours of manual code review
- 📚 **Instant Documentation** - Never write documentation again
- 🔒 **Security First** - Identify vulnerabilities early
- 📊 **Visual Insights** - Understand your codebase better
- 🤖 **AI-Powered** - Powered by Google's most advanced AI

---

## ✨ Key Features

### 🔍 Code Analysis
| Feature | Description |
|---------|-------------|
| **Deep Code Understanding** | Uses AST parsing for comprehensive code analysis |
| **Multi-language Support** | Python, JavaScript, Java, Go, Rust, and more |
| **Complexity Analysis** | Cyclomatic complexity, maintainability index |
| **Dependency Visualization** | Interactive dependency graphs |
| **Code Metrics** | Lines of code, function count, class count |

### 🤖 AI-Powered Review
| Feature | Description |
|---------|-------------|
| **Code Quality Assessment** | Gemini-powered code quality scoring |
| **Security Scanning** | Vulnerability detection (SQL injection, XSS, etc.) |
| **Performance Analysis** | Optimization suggestions |
| **Best Practices** | Industry-standard code recommendations |
| **Refactoring Suggestions** | AI-driven code improvement recommendations |

### 📚 Auto Documentation
| Feature | Description |
|---------|-------------|
| **README Generation** | Professional README with project structure |
| **API Documentation** | Swagger/OpenAPI spec generation |
| **Inline Comments** | Smart code commenting suggestions |
| **Architecture Diagrams** | Visual system architecture creation |
| **User Guides** | Automated user documentation |

### 🧪 Testing
| Feature | Description |
|---------|-------------|
| **Test Generation** | Automatic unit test creation |
| **Coverage Analysis** | Test coverage recommendations |
| **Edge Cases** | Identification of test scenarios |
| **Test Suites** | Complete test suite generation |

### 📊 Analytics
| Feature | Description |
|---------|-------------|
| **Code Metrics Dashboard** | Visual quality metrics |
| **Trend Analysis** | Code quality trends over time |
| **Team Analytics** | Team performance insights |
| **Reports** | Exportable PDF/HTML reports |

---

## 🛠️ Tech Stack

### Backend


---

## 🚀 Installation

### Prerequisites
| Requirement | Version |
|-------------|---------|
| Python | 3.10+ |
| Node.js | 18+ |
| PostgreSQL | 14+ |
| Redis | 6+ |
| Git | Latest |
| Docker | 20+ (optional) |

### Step 1: Clone the Repository
```bash
git clone https://github.com/vishakha2121/AI-Powered-Code-Review-Documentation-Generator.git
cd AI-Powered-Code-Review-Documentation-Generator

# Create virtual environment
cd backend
python -m venv venv

# Activate virtual environment
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Install development dependencies (optional)
pip install -r requirements-dev.txt


cd frontend
npm install