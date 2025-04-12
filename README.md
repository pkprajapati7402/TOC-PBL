# 🎯 Regular Expression to DFA Converter (Parse Tree Method)

🔗 **Live Demo:** [Try it here](https://regular-expression-to-dfa-parse-tree-method-online.vercel.app/)

This web application allows users to convert **regular expressions directly into Deterministic Finite Automata (DFA)** using the **Parse Tree Method** — bypassing the traditional NFA-to-DFA transformation. It's designed to aid learning and exploration in formal languages and automata theory.



## 📌 About the Project

This tool is ideal for:
- 🎓 Computer Science students studying formal language theory.
- 👨‍🏫 Educators demonstrating regex-to-DFA transformations.
- 👨‍💻 Developers curious about how regex relates to finite automata.


## 🔍 What is the Parse Tree Method?

The Parse Tree Method allows direct construction of a DFA from a regular expression, avoiding intermediate steps like converting to an NFA. It involves:
- Constructing a **parse tree**
- Computing **nullable, firstpos, lastpos**
- Building a **followpos table**
- Generating the **DFA transition table**

This method is an elegant alternative to the classical Subset Construction algorithm.

👉 [Learn more on GeeksForGeeks](https://www.geeksforgeeks.org/regular-expression-to-dfa/)


## 🚀 Features

- Supports standard regex operations:
  - Concatenation (`ab`)
  - Alternation (`a|b`)
  - Kleene Star (`a*`)
  - Plus (`a+`)
  - Optional (`a?`)
  - Epsilon (`ε`, `""`, or `∈`)
- Clean and interactive UI
- Step-by-step generation of:
  - Parse Tree
  - Follow Pos Table
  - Transitions Table
  - DFA State Diagram


## 🛠️ How to Use

1. Enter your regular expression in the input field (examples are available).
2. Click **Generate DFA**.
3. Visualize:
   - Parse Tree
   - Follow Position Table
   - Transition Table
   - DFA Graph


## ✅ Output Includes

- 📄 **Parse Tree:** Shows hierarchical structure of the expression.
- 📊 **Follow Position Table:** Maps regex positions to follow positions.
- 🔁 **Transition Table:** Represents DFA state transitions.
- 🔗 **DFA Graph:** Visual diagram of the resulting DFA.



## ⚠️ Known Limitation

Currently, the tool does **not support** regex patterns composed solely of epsilon symbols (e.g., `ε|ε?`). While theoretically this results in a single accepting state with no transitions, support for such edge cases is under consideration for future updates.



## 📎 License & Contribution

This project is open-source and intended for educational use. Contributions, improvements, and bug reports are welcome!

---

