---

# 🕒 Pomodoro Timer

## README

### 📌 Overview
This project is a **Pomodoro Timer** built using Python’s `tkinter` library. It helps users manage their work and break intervals using the Pomodoro technique — a time management method that alternates focused work sessions with short and long breaks.

### 🚀 Features
- **Work & Break Cycles**: Automatically switches between work, short breaks, and long breaks.
- **Customizable Durations**: Easily adjust work, short break, and long break times.
- **Visual Timer**: Displays countdown in minutes and seconds.
- **Progress Tracking**: Shows check marks for completed work sessions.
- **Reset Functionality**: Allows users to reset the timer and progress at any time.

### 🛠️ Requirements
- Python 3.x
- `tkinter` (comes pre-installed with Python)
- `tomato.png` image file (used for the timer UI)

### 📂 Project Structure
```
pomodoro_timer/
│── pomodoro.py        # Main application script
│── tomato.png         # Image used in the timer UI
│── README.md          # Documentation
```

### ▶️ How to Run
1. Clone or download the project files.
2. Ensure `tomato.png` is in the same directory as the script.
3. Run the script:
   ```bash
   python pomodoro.py
   ```
4. Use the **Start** button to begin the timer and the **Reset** button to reset progress.

### 🎯 Pomodoro Technique
- **Work Session**: 25 minutes (default, adjustable in code)
- **Short Break**: 5 minutes
- **Long Break**: 20 minutes (after 4 work sessions)

### 📌 Customization
You can change the session durations by modifying these constants in the script:
```python
WORK_MIN = 25
SHORT_BREAK_MIN = 5
LONG_BREAK_MIN = 20
```

---

