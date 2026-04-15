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

### 🚀 Launch the Project

To view the interactive project in your browser, follow these steps:

1. **Open in VS Code:** Open the cloned folder in Visual Studio Code.
2. **Start Live Server:** * Locate the `index.html` file in the file explorer.
   * Right-click the file and select **"Open with Live Server"**.
   * Alternatively, click the **"Go Live"** button in the bottom status bar.

---

## 👩‍💻 Author

> **Sakshi** > Built for learning **Theory of Automata & Formal Languages** in an interactive way 🎓
