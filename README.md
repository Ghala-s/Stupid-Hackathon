
Inspiration
I was tired of productivity apps that makes me feel guilty for not completing tasks. Why should software judge us? What if, instead of pushing us to be better, it just... gave up when we did? Thus, MoodToDo was born: the world's first emotionally intelligent to-do list that validates your desire to do absolutely nothing.

What it does
MoodToDo is a to-do list that syncs with your current emotional state. It uses your webcam and a highly questionable sentiment analysis algorithm to decide what to do with your tasks.

Calm & Neutral: Shows your tasks normally. Boring, but functional.

Tired & Sad: Deletes all your tasks automatically. "You looked tired, so we cleared your schedule. You're welcome."

Happy & Joyful: Hides all tasks and displays: "Good job! Keep that smile! 😊 (Your tasks are still there... somewhere... but who cares? You're happy!)"


How we built it
Frontend: React with excessive CSS animations for emotional flair

Mood Detection: A very simplistic facial expression analysis library that mostly just guesses

Task Management: Local storage (because your tasks probably shouldn't be permanent anyway)

The "AI": Basically just if/else statements with extra steps and questionable accuracy

Special Sauce: Pure nihilism mixed with digital empathy


Why it's useless
It actively destroys your productivity system by deleting tasks when you need them most

The mood detection is comically inaccurate - a yawn might delete your entire week's work

It encourages emotional avoidance - better stay happy or you'll lose your task list!

It solves a problem that doesn't exist by creating several new, more interesting problems

Perfect for people who want the illusion of productivity without any of the actual work!

🚀 How to Run This Beautiful Disaster

bash
# 1. Navigate to your project folder
cd my-mood-todo

# 2. Start a local server (Python 3)
python -m http.server 8000
Then:

Open your browser (Chrome/Edge recommended)

Go to: http://localhost:8000

Allow camera access when prompted (CRITICAL - or the mood detection won't work!)
