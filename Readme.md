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
   git clone https://github.com/sonali8412/wingsai.git
   cd wingsai
