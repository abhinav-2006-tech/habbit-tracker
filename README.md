# Nexus Focus 🚀
### Your Personal Productivity & Wellness Dashboard

Nexus Focus is a productivity and wellness web application designed to help users organize daily tasks, build consistent habits, improve concentration, and track personal wellness through a modern, interactive dashboard.

Built with HTML, CSS, and JavaScript, the application combines task planning, focus sessions, productivity insights, and health tracking in one place.

## ✨ Features

### 📅 1. Task & Mission Planner
- Create, edit, and delete tasks.
- Schedule tasks for specific dates.
- Organize tasks into Work, Life, Health, and Focus categories.
- Assign High, Medium, or Low priorities.
- Track task completion and daily productivity.
- View a calendar strip to navigate dates.
- Monitor daily progress with a visual progress indicator.

### 🎯 2. Focus Timer
- Pomodoro-style focus sessions.
- Choose between 25-minute focus / 5-minute break and 50-minute focus / 10-minute break sessions.
- Start, pause, reset, or skip sessions.
- Receive notifications when a session finishes.
- Visual timer with animated progress indicators.

### ⏰ 3. Smart Task Reminders
- Set timed alerts for scheduled tasks.
- Choose from multiple alert sounds.
- Receive in-app alarm overlays and browser notifications when permission is granted.
- Mark a task as complete directly from an alarm.

### 🔥 4. Habit Building
- Add predefined daily habits.
- Create custom habits and assign categories.
- Remove habits that are no longer needed.
- Track consistency with a daily streak counter.
- Celebrate completed tasks with visual confetti effects.

### 💧 5. Wellness & Health Tracking
- Track daily water intake.
- Receive hydration reminders.
- Track steps using device motion events where supported.
- Record blood sugar readings.
- Log systolic and diastolic blood pressure.
- Review recent health readings.
- Record the last menstrual period and configure cycle length.
- Estimate the next period date based on the entered cycle length.

### 📊 6. Productivity Insights
- Track task completion and productivity progress.
- Encourage consistency through motivational messages and streak tracking.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling, animations, and responsive visual elements |
| JavaScript | Application logic and interactivity |
| Local Storage | Persisting tasks, habits, and wellness data |
| Browser Notifications API | Task alerts and focus notifications |
| HTML Audio API | Playing reminder sounds |
| Device Motion API | Basic motion-based step estimation |
| Google Fonts — Inter | Typography |

## 📂 Project Structure

```text
Nexus-Focus/
│
├── index.html     # Main application, styling, and JavaScript
└── README.md      # Project documentation
```

The application is currently implemented as a single HTML file containing its markup, CSS, and JavaScript.

## 🚀 Getting Started

### Prerequisites

- A modern web browser such as Google Chrome, Microsoft Edge, or Firefox.
- A code editor such as Visual Studio Code (optional).

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

**2. Open the project folder**

```bash
cd YOUR-REPOSITORY
```

**3. Run the application**

Open `index.html` directly in your browser.

Alternatively, use the Live Server extension in Visual Studio Code:

1. Open the project folder in VS Code.
2. Install the Live Server extension if needed.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

No backend server or package installation is required for the current implementation.

## 💾 Data Storage & Privacy

Nexus Focus uses the browser's `localStorage` to save application data, including tasks, habits, and health records.

- Data is stored locally in the browser.
- Data is not automatically synchronized across devices.
- Clearing browser storage may permanently remove saved records.
- Reminder sounds are loaded from external Mixkit URLs.
- Google Fonts is used to load the Inter typeface.

**Important:** Health-related entries are user-recorded tracking data and are not a substitute for professional medical advice.

## 📱 Browser Compatibility

The core application is designed for modern browsers. Certain features depend on browser support and permissions:

- Notifications require browser permission.
- Audio playback may require user interaction.
- Device motion tracking depends on device hardware, browser support, and permission settings.
- Timed alerts work while the page's JavaScript is running; they are not guaranteed to fire if the browser or page is closed or suspended.

## 🔮 Future Improvements

Potential enhancements include:

- Responsive layouts optimized for mobile devices.
- Weekly and monthly productivity charts.
- Advanced habit analytics and customizable goals.
- Improved step counting and activity tracking.
- Export and backup of user data.
- Dark/light theme customization.
- Cloud synchronization and user authentication.
- More flexible recurring tasks and reminders.
- Accessibility improvements.

## 🤝 Contributing

Contributions and suggestions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Commit and push your work.
5. Open a pull request.

## 📄 License

No license has been specified yet. Add a `LICENSE` file if you intend to distribute this project under a particular open-source license.

---

**Nexus Focus — Plan with purpose. Focus with intention. Grow every day.**
