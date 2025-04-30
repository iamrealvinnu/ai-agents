🚀 TaskFlow Agent by NeuraX AI: Your AI-Powered Productivity Wingman!
Ever wished for a task manager that thinks for you? Say hello to TaskFlow Agent by NeuraX AI—a futuristic, AI-driven tool that auto-categorizes tasks, spots conflicts, and wraps it all in a jaw-dropping holographic UI. Built with React and a sprinkle of AI magic, this project is here to redefine how you tackle your day. Let’s dive in! 🎉
What’s TaskFlow Agent?
TaskFlow Agent is more than a to-do list—it’s a productivity powerhouse. Powered by NeuraX AI, it uses keyword-based AI to auto-categorize tasks (e.g., “Client Meeting” as Work, “Buy Grocery” as Other), suggests optimal time slots, and keeps your schedule conflict-free. Oh, and did we mention the UI? Think holographic task cards, animated data streams, and a midnight blue gradient that screams “future.” Ready to level up your workflow?
✨ Key Features

AI Auto-Categorization: Drops tasks into Work, Personal, or Other using keyword logic—like client for Work or gym for Personal.
Conflict Detection: Spots overlapping schedules and warns you (e.g., two Morning tasks).
Smart Scheduling: Suggests time slots based on priority (e.g., Morning for high-priority tasks).
Sleek UI: Holographic cards with flip-in animations, pulsing data streams, and a light/dark mode toggle.
Task Management: Sort by priority, time, or category, mark tasks complete, and export as JSON.

🎥 See It in Action
Check out this 45-60 second demo to witness TaskFlow Agent’s magic—from auto-categorizing tasks to its futuristic UI.

https://drive.google.com/file/d/1qzVCBeT5xxJ8G64nSyG8Cd0-ZBzwaO-x/view?usp=sharing

🖼️ Screenshots
Input Hub: Where the Magic Starts
Enter tasks, toggle modes, and let AI categorize—like “Client Meeting” as Work!
Task List: Holographic & Smart
See tasks like “Buy Grocery” auto-tagged as Other, with sorting and actions.

![tf1](https://github.com/user-attachments/assets/5704f168-79f2-4546-9c6c-5e613ecf2453)
![tf2](https://github.com/user-attachments/assets/277a9c76-1c67-482d-b082-40936c1bc5e4)


🛠️ Tech Stack

Frontend: React 18 (via CDN) for dynamic rendering.
Transpilation: Babel (@7) for in-browser JSX support.
Styling: Pure CSS with animations (e.g., flipIn for task cards, flow for data streams).
AI Logic: Keyword-based categorization (e.g., categorizeTask function with arrays like workKeywords).
Fonts: Manrope from Google Fonts for a modern look.

🚀 Get Started
Since TaskFlow Agent runs as a single HTML file with CDNs, setup is a breeze—no Node.js required!

Clone the Repo:
git clone https://github.com/[YOUR_USERNAME]/[YOUR_REPO].git
cd [YOUR_REPO]


Run Locally:

Install the “Live Server” extension in VS Code.
Right-click index.html and select “Open with Live Server” (runs at http://127.0.0.1:5500).
Alternatively, use a simple HTTP server:npm install -g http-server
http-server

Open http://localhost:8080 in your browser.


Explore the Code:

index.html: Contains the full app—HTML, CSS, and JavaScript.
React hooks (useState, useEffect) manage state (e.g., tasks, theme).
CSS animations like @keyframes flipIn bring task cards to life.
AI logic in categorizeTask uses keyword arrays for smart categorization.



🎮 How to Use





Add a Task: Type “Client Meeting” or “Out for a Walk” in the input hub. Watch AI auto-categorize!



Set Urgency: Choose Low, Medium, or High to adjust priority scores.



Sort & Manage: Sort tasks by priority, time, or category. Mark them complete or export as JSON.



Switch Modes: Toggle light/dark mode for a personalized vibe.

🤝 Contribute
Love TaskFlow Agent? Join the party! Fork the repo, tweak the code, and submit a pull request. We’d love to see new features, UI enhancements, or AI improvements. Just keep it clean and add comments for clarity.
📜 License
This project is under the MIT License. Check the LICENSE file for details.
🌟 Shoutouts
Big thanks to the NeuraX AI crew for the vision, React for the magic, and the open-source community for endless inspiration. Let’s keep pushing productivity forward! 🚀
