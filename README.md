---
## To-Do List Web App

A simple, elegant, and responsive **To-Do List** application built using **HTML**, **CSS**, and **Vanilla JavaScript**. This project allows users to manage their tasks efficiently with local storage support, no backend required.

![WhatsApp Image 2025-09-25 at 11 54 52_fbb906a6](https://github.com/user-attachments/assets/32258487-1176-4bc6-a424-fc077ac52eae)

---

## Features

- Add new to-do items
- Edit existing tasks inline
- Mark tasks as complete/incomplete
- Delete all tasks
- Persistent storage using `localStorage`
- Fully responsive and mobile-friendly design

---

## Tech Stack

| Layer       | Technology         |
|-------------|--------------------|
| Markup      | HTML5              |
| Styling     | CSS3               |
| Behavior    | JavaScript (ES6+)  |
| Storage     | Browser `localStorage` |

---

## Project Structure

```

todo_app/todo
├── index.html          # Main HTML structure
├── style.css           # Styling and layout
├── script.js           # JS logic for the app

````

## How It Works

- Tasks are stored as objects in an array, and saved to `localStorage`.
- When the page loads, it checks for any existing tasks and renders them.
- Each task supports:
  - Checkbox to toggle completion
  - Click-to-edit functionality
  - Delete all tasks button
- Styling is handled with custom CSS, including scrollbars and responsive design.

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/harini08k/todo_app.git
cd todo_app
````

### 2. Open in Browser

No build steps required. Just open `index.html` in your browser:

```bash
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

---

## 📸 Screenshots

![WhatsApp Image 2025-09-25 at 11 52 41_762d22ee](https://github.com/user-attachments/assets/88195e17-f358-4171-905f-44fbec76b6ff)
![WhatsApp Image 2025-09-25 at 11 53 58_c954ec85](https://github.com/user-attachments/assets/c58d1ffd-ba04-489d-a36d-bc4eaabfdda2)

---

## 👩‍💻 Author

**Harini Karthikeyan**
[GitHub Profile](https://github.com/harini08k)

---

## 🙌 Acknowledgements

* Vanilla JS To-Do app inspiration from beginner-friendly UI challenges
* LocalStorage documentation - [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)

````
