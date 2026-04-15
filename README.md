⚡ TAFL Regex Explorer

An interactive web-based tool designed for students studying Theory of Automata & Formal Languages (TAFL).
It helps visualize, understand, and experiment with regular expressions in a simple and engaging way.

🚀 Features
🔹 Regex String Generator
Generate all strings accepted by a regex up to a chosen length
Strings grouped by length
Supports ε (empty string)
Animated and clean output display
🔹 Equivalence Checker
Check whether two regular expressions define the same language
Provides counterexample if not equivalent
Uses intelligent sampling for comparison
🔹 Symbol Palette
Click-to-insert regex symbols
Includes:
Literals (a, b, 0, 1, etc.)
Operators (|, ., ())
Quantifiers (*, +)
🔹 Live Matcher
Test any string against your regex in real-time
Instant match / no match feedback
🔹 Plain English Explanation
Converts regex into beginner-friendly explanation
Helps in understanding patterns quickly
🔹 Preset Examples
Pre-built regex patterns for quick testing
Includes common patterns like:
(a|b)*
\d+
[a-z]+
⚙️ How to Run Locally
Clone the repository:
git clone https://github.com/Sakshi7654/tafl-regex-project.git
Open the folder in VS Code
Run the project:
Simply open index.html in your browser
🧠 How It Works
🔸 String Generation
Uses BFS (Breadth-First Search) to generate strings
Tests strings using JavaScript RegExp
Limits length to avoid explosion
🔸 Equivalence Checking
Generates a large sample set of strings
Compares acceptance of both regex
Returns:
✅ Equivalent
❌ Not Equivalent + counterexample
🎯 Use Cases
Learning Regular Expressions
Understanding Automata concepts
Practicing regex problems
🙌 Contribution

Feel free to fork and improve the project!
Pull requests are welcome 🚀

💡 Author

Developed by Sakshi
For learning and exploring TAFL concepts in an interactive way 🎓
