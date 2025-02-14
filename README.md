# 📌 Crossword Puzzle Solver

A **constraint satisfaction problem (CSP)-based crossword generator** that constructs and solves crossword puzzles using AI techniques such as **backtracking search, node consistency, and arc consistency**.

---

## 🚀 Features

✅ Generates crossword puzzles from a given structure and word list.\
✅ Uses **constraint satisfaction problem (CSP)** techniques to efficiently fill the crossword.\
✅ Implements **backtracking, node consistency, and arc consistency (AC-3)** algorithms.\
✅ Supports **custom structure files** and **word lists**.\
✅ Saves the final crossword as an image.\
✅ Command-line interface (CLI) support for easy execution.

---

## 📂 Project Structure

```
/crossword-project
│-- crossword.py       # Defines crossword grid structure & constraints
│-- generate.py        # CSP-based crossword generator & solver
│-- assets/fonts/      # Fonts for crossword image generation
│-- README.md          # Documentation
```

---

## 🔧 Installation & Setup

### **1️⃣ Clone the Repository**

```sh
git clone https://github.com/your-username/crossword-project.git
cd crossword-project
```

### **2️⃣ Install Dependencies**

This project requires Python **3.x** and Pillow for image rendering.

```sh
pip install -r requirements.txt  # If a requirements file exists
```

If dependencies are missing, install Pillow manually:

```sh
pip install pillow
```

### **3️⃣ Run the Crossword Generator**

```sh
python generate.py structure.txt words.txt output.png
```

- `structure.txt`: Defines the crossword layout (use `_` for empty spaces, `#` for blocked spaces).
- `words.txt`: List of words to fit in the puzzle.
- `output.png`: (Optional) Saves the crossword as an image.

Example:

```sh
python generate.py example_structure.txt example_words.txt output.png
```

---

## 🖥️ How It Works

1️⃣ **Crossword Grid Definition**: Reads `structure.txt` and defines open spaces.\
2️⃣ **Word Assignment & Constraints**: Uses **CSP techniques** to ensure valid word placement.\
3️⃣ **Backtracking Search**: Efficiently assigns words to the crossword grid.\
4️⃣ **Image Generation**: Converts the solution into a visually appealing crossword image.

---

## 📜 License

This project is licensed under the **MIT License**. Feel free to use and modify it.

---

## 👨‍💻 Author

✉️ **Chinmay Sumbe**\
🔗 [LinkedIn](https://www.linkedin.com/in/chinmay-sumbe/)\
🐙 [GitHub](https://github.com/ChinmaySumbe)

---

### 🌟 If you like this project, give it a ⭐ on GitHub!

