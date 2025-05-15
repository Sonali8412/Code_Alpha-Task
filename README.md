# 🤖 WingsAI – Java Desktop Chatbot

**WingsAI** is a personal desktop-based AI chatbot built using **Java Swing**. It interacts with users through a graphical interface and performs various local tasks such as opening programs, displaying the current time/date, and running scripts based on user input.

---

## 🧠 Features

🔹 Friendly graphical user interface (GUI)  
🔹 Recognizes user queries like:
  - Greetings: `"hi"`, `"hello"`
  - Personal questions: `"Who are you?"`, `"How are you?"`
  - Utility commands: `"open calculator"`, `"show date/time"`
  - Launches local `.vbs` and `.bat` scripts  
🔹 Responds with preset answers and triggers using **regex pattern matching**  
🔹 Basic natural language processing via `String.matches()`  

---

## 🛠️ Tech Stack

🔹 **Java** – Core programming language  
🔹 **Java Swing** – Used for GUI design  
🔹 **Regex** – To parse and understand user inputs  
🔹 **Desktop API** – To open local files and apps  

---

## 🚀 How to Run

### ✅ Prerequisites

🔸 Java JDK 8 or above installed  
🔸 Windows OS (as `.vbs` and `.bat` files are platform-specific)  
🔸 Update hardcoded file paths in `WingsAI.java` to your local setup  

---

### ▶️ Steps to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Sonali8412/Code_Alpha-Task.git
   cd wingsai


---

 📂 File Paths (Important!)

WingsAI relies on hardcoded paths like:

```
C:\Users\salok\OneDrive\Desktop\ai\ai\temp14659.vbs
```

🔧 You must replace these paths with valid paths on your machine or use relative paths for portability.



 🖼️ Screenshot

![WingsAI Screenshot](./screenshots/wingsai-sample.png) <!-- Replace with your actual screenshot path -->



⚙️ Example Commands

* `Hi`, `Hello`, `Hey` – Greets you back
* `How are you?` – Responds politely and asks about you
* `Who are you?` – Describes itself
* `Open calculator` – Opens a local calculator script
* `SiteSelector` – Opens a site selection script
* `Date` or `Time` – Displays the current date and time

---

 🙋 About the Creator

WingsAI was created by **Sonali** as a personal assistant project using core Java.

---

📜 License

This project is licensed under the MIT License – feel free to use, modify, and share.

---

 📬 Contact

* GitHub: https://github.com/Sonali8412
* Email: sonaligupta3244@gmail.com




Let me know if:
- You’d like help turning those hardcoded paths into relative or configurable ones
- You plan to upload this to GitHub and need help creating a `screenshots` folder or `.gitignore` file

I can also help clean up and organize your code for better readability if you’d like!


`
