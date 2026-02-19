# 📊 Task Tracker Dashboard

A simple task management dashboard built using HTML, CSS, JavaScript, and Chart.js.

This project allows users to add and delete tasks while dynamically updating a bar chart that displays the total number of tasks.

---

## 🚀 Features

- Add new tasks
- Delete tasks
- Live task counter
- Dynamic bar chart using Chart.js
- Clean dashboard layout with sidebar
- Responsive flexbox design

---

## 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Chart.js (CDN)

---

## 📂 Project Structure

task-tracker-dashboard/
│
├── index.html
└── README.md

---

## 📈 How It Works

1. User enters a task and clicks Add.
2. Task gets appended to the list.
3. Task count increases.
4. The bar chart updates automatically.
5. When a task is deleted:
   - Count decreases
   - Chart updates dynamically

The chart updates using:

    chart.data.datasets[0].data[0] = count;
    chart.update();

---

## 🔧 Setup Instructions

1. Clone the repository:

    git clone https://github.com/AnanyaMesta02/task-tracker-dashboard.git

2. Open the folder.
3. Open index.html in your browser.

No installation required.

---

## 🎯 Learning Outcomes

- DOM manipulation
- Event handling
- Working with external libraries (Chart.js)
- Dynamic UI updates
- Git & GitHub workflow

---

## 📌 Future Improvements

- Store tasks in localStorage
- Add completed task status
- Add task categories
- Add multiple chart types
- Improve UI design

---

## 👩‍💻 Author

Ananya Mesta  
Engineering Student
