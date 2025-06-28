# CompilerPbl
A web-based Compiler Phase Visualizer with support for Lexical, Syntax, Semantic Analysis, and Intermediate Code Generation. Built using HTML, CSS, JavaScript, SVG, and Flask.

---

## 🔍 What This Project Covers

This visualizer covers the following compiler phases:

- ✅ **Lexical Analysis** (with token generation)
- ✅ **Syntax Analysis** (parse tree construction)
- ✅ **Semantic Analysis**
- ✅ **Intermediate Code Generation (ICG)**
- ✅ **Code Optimization Concepts** *(through PDFs)*
- 📚 **Detailed notes and theory** for learning

---

## 📂 Project Structure
compilerpbl/
├── app.py # Main Flask application
├── lexer.py # Lexical analyzer logic
├── parser.py # Syntax analyzer with grammar
├── parsetab.py # Generated parse table
├── semantic.py # Semantic analyzer
├── test.py # Sample input/test runner
├── static/
│ ├── style.css # Custom styles
│ ├── script.js # Page handling scripts
│ ├── tree.js # Parse tree visualization (SVG)
│ ├── asset/
│ │ └── phasesofcompiler.jpg
│ └── notes/ # PDF notes for theory reference
│ ├── *.pdf # 10+ PDFs on compiler concepts
├── templates/
│ ├── index.html # Homepage
│ ├── lexical.html # Lexical output page
│ ├── syntax.html # Parse tree output
│ ├── semantic.html # Semantic analysis result
│ ├── intermediate.html # Intermediate code output
│ ├── generation.html # Placeholder for code generation
│ ├── optimization.html # Optimization notes
│ └── notes.html # Study materials
