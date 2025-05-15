

---

````markdown
# 🤖 WingsAI – Java Desktop Chatbot

**WingsAI** is a personal desktop-based AI chatbot built using **Java Swing**. It interacts with users through a graphical interface and performs various local tasks such as opening programs, displaying the current time/date, and running scripts based on user input.

---

## 🧠 Features

- Friendly graphical user interface (GUI)
- Recognizes user queries like:
  - Greetings: "hi", "hello"
  - Personal questions: "Who are you?", "How are you?"
  - Utility commands: "open calculator", "show date/time"
  - Launches local `.vbs` and `.bat` scripts
- Responds with preset answers and triggers based on regex matching
- Basic form of natural language processing using Java `String.matches()`

---

## 🛠️ Tech Stack

- **Java** – Core programming language
- **Java Swing** – For GUI design
- **Regex** – Used to parse user inputs
- **Desktop API** – To open external files/applications

---

## 🚀 How to Run

### Prerequisites

- Java JDK 8 or above installed
- Windows OS (since `.vbs` and `.bat` files are used)
- Modify hardcoded file paths to match your local setup

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/wingsai.git
   cd wingsai
````

2. Compile and run:

   ```bash
   javac WingsAI.java
   java WingsAI
   ```

---

## 📂 File Paths (Important!)

WingsAI relies on hardcoded paths like:

```
C:\Users\salok\OneDrive\Desktop\ai\ai\temp14659.vbs
```

🔧 You **must replace** these paths with valid paths on your machine or use relative paths for portability.

---

## 🖼️ Screenshot

![WingsAI Screenshot](./screenshots/wingsai-sample.png) <!-- Replace with your actual screenshot path -->

---

## ⚙️ Example Commands

* `Hi`, `Hello`, `Hey` – Greets you back
* `How are you?` – Responds politely and asks about you
* `Who are you?` – Describes itself
* `Open calculator` – Opens a local calculator script
* `SiteSelector` – Opens a site selection script
* `Date` or `Time` – Displays the current date and time

---

## 🙋 About the Creator

WingsAI was created by **Sonali** as a personal assistant project using core Java.

---

## 📜 License

This project is licensed under the MIT License – feel free to use, modify, and share.

---

## 📬 Contact

* GitHub: [yourusername](https://github.com/yourusername)
* Email: [your.email@example.com](mailto:your.email@example.com)

`
