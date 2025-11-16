# MoodToDo™

> The world's first emotionally intelligent to-do list that validates your desire to do absolutely nothing.

---

## Inspiration

I was tired of productivity apps that make me feel guilty for not completing tasks.  
Why should software judge us?  

What if, instead of pushing us to be better, it just… gave up when we did?  

Thus, **MoodToDo** was born: a to-do list that *syncs with your mood* and occasionally ruins your productivity.  

---

## What It Does

MoodToDo adjusts your tasks based on your emotional state using your webcam and a highly questionable sentiment analysis algorithm.

- **Calm & Neutral**: Shows your tasks normally. Boring, but functional.  
- **Tired & Sad**: Deletes all your tasks automatically.  
  > "You looked tired, so we cleared your schedule. You're welcome."  
- **Happy & Joyful**: Hides all tasks and displays:  
  > "Good job! Keep that smile! 😊 (Your tasks are still there... somewhere... but who cares? You're happy!)"  

---

## How We Built It

- **Frontend**: HTML/CSS/JS with enough animations to cause seizures  
- **Face Detection**: `face-api.js` to judge your facial expressions  
- **Task Storage**: JavaScript objects (because your commitment to tasks is temporary anyway)  

---

## Why It's Useless

- It actively destroys your productivity by deleting tasks when you need them most   
- Encourages emotional avoidance—stay happy or lose your task list!  
- Solves a problem that doesn't exist by creating several new, more interesting problems  
- Perfect for people who want the illusion of productivity without any of the actual work  

---

## 🚀 How to Run This Beautiful Disaster

```bash
# 1. Navigate to your project folder
cd my-mood-todo

# 2. Start a local server (Python 3)
python -m http.server 8000

Then:

Open your browser (Chrome/Edge recommended)

Go to: http://localhost:8000

Allow camera access when prompted (CRITICAL - or the mood detection won't work!)
