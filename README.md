# ⚡ TAFL Regex Explorer

An interactive web-based tool for **Theory of Automata & Formal Languages (TAFL)** that helps students explore, visualize, and understand **regular expressions**.

---

## 🚀 Features

### 🔹 Regex String Generator
- Generate all strings accepted by a regex up to a chosen length  
- Strings grouped by length  
- Supports empty string (ε)  
- Clean and animated UI  

### 🔹 Equivalence Checker
- Check if two regular expressions are equivalent  
- Shows **counterexample** when they are not  
- Smart sampling-based comparison  

### 🔹 Symbol Palette
- Click-to-insert regex symbols  
- Includes literals, operators, and quantifiers  

### 🔹 Live Matcher
- Test strings against regex in real-time  
- Instant match / no match feedback  

### 🔹 Plain English Explanation
- Converts regex into simple explanations  
- Beginner-friendly learning support  

### 🔹 Preset Examples
- Ready-to-use regex patterns for quick testing  

---

## 🖥️ Tech Stack

- HTML  
- CSS (Dark theme + modern UI)  
- JavaScript (Vanilla JS)

---

## 🧠 How It Works

### 🔸 String Generation
- Uses **Breadth-First Search (BFS)** to generate possible strings  
- Limits string length to avoid infinite expansion  
- Validates each string using JavaScript `RegExp`  

### 🔸 Equivalence Checking
- Generates a large sample set of strings  
- Tests both regex on each string  
- If any mismatch is found:
  - Returns a **counterexample**
- Otherwise:
  - Marks them as **equivalent (within tested range)**  

---

## ⚙️ How to Run Locally

Follow these steps to set up and run the project on your local machine:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Sakshi7654/tafl-regex-project.git
---
-Open with live server

## 👩‍💻 Author

**Sakshi**  
Built for learning **Theory of Automata & Formal Languages** in an interactive way 🎓
