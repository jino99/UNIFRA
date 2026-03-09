# UNIFRA
UNIFRA - Intelligent University Management
UNIFRA is a comprehensive, single-page web application designed to help university students organize their study schedules, track their academic progress, and maintain a healthy study-life balance. Built entirely as a client-side application, it requires no backend and stores all data locally in the user's browser.

🌟 Key Features
Smart Study Planner: Automatically calculates your daily study tasks based on the total pages, exam date, and a customizable "review phase" buffer.

Comprehensive Dashboard: Displays a countdown to your next exam, today's specific tasks, and active exam progress bars.

Exam & Grade Management (Libretto): Tracks your active exams and completed exams, automatically calculating your total credits (CFU) and weighted average.

Degree Simulator: Calculates your starting graduation grade based on your current average and allows you to input a target grade to see the average you need to maintain for your remaining exams.

Wellness Tools: Features an integrated Pomodoro timer with audio notifications and a daily water tracker to encourage healthy study habits.

Data Portability: Includes built-in tools to export your entire database as a JSON backup and import it across different devices.

💻 Technology Stack
UNIFRA is built to be lightweight and easy to deploy, using modern web standards without the need for a build pipeline or server:

Structure: HTML5

Styling: Tailwind CSS (via CDN) and custom CSS with glassmorphism effects

Icons & Typography: Font Awesome and Google Fonts (Poppins)

Logic & State: Vanilla JavaScript utilizing localStorage for data persistence

🚀 Getting Started
Because UNIFRA is a purely client-side application, installation is incredibly simple:

Download or clone this repository.

Locate the unifra.html file.

Double-click the file to open it in any modern web browser (Chrome, Firefox, Safari, Edge).

Start adding your exams and tracking your progress!

⚙️ How the Algorithm Works
The application uses a dynamic scheduling algorithm to keep you on track:

Input: You define an exam with a date, total pages, and priority.

Review Buffer: The app sets aside a percentage of your total preparation time (default is 35%) specifically for reviewing.

Daily Target: It divides the remaining pages by your available study days to give you a clear, achievable daily goal, updating your task list every day.
