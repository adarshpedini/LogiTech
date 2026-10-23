# LogicIQ — Logic & Data Interpretation Platform

LogicIQ is an interactive, responsive learning website designed to help students improve their logical reasoning and data interpretation skills for competitive examinations and placement assessments.

The platform follows a simple learning cycle: **Learn → Solve → Practice**. Users can study concepts, work through problems with interactive calculators, take quizzes, and track their learning progress.

## Screenshots

### Home Dashboard
The home page introduces LogicIQ, displays learning statistics, and provides quick access to popular topics.

![LogicIQ Home Dashboard](screenshots/home.png)

### Mixed Practice Quiz
The mixed quiz presents multiple-choice questions from different topics and provides an interactive practice experience.

![LogicIQ Mixed Quiz](screenshots/practice.png)

### Learning Progress
The progress dashboard displays XP earned, questions answered, accuracy, best streak, and topic-wise performance.

![LogicIQ Progress Dashboard](screenshots/progress.png)

> **Adding screenshots:** Create a folder named `screenshots` in your project repository and place the corresponding images there using the filenames `home.png`, `practice.png`, and `progress.png`. Update the filenames in this README if yours are different.

## Key Features

- **Ten learning topics** covering logical reasoning, data interpretation, and charts.
- **Learn, Solve, and Practice:** Each topic provides concept notes, a solver/calculator where applicable, and multiple-choice questions.
- **Topic library:** Browse topics using search and category filters.
- **Mixed practice quiz:** Answer a set of 10 questions drawn from different topics.
- **Instant feedback:** Check answers and view explanations in practice quizzes.
- **Formula reference:** Review important formulas and problem-solving tips.
- **Progress dashboard:** Track XP, answered questions, accuracy, streaks, and topic-wise performance.
- **Automatic browser saving:** Learning progress is stored locally in the browser.
- **Responsive interface:** Designed for desktop, tablet, and mobile screens.
- **Dark theme:** Dark panels with purple accents and clear interactive controls.

## Topics Covered

| Category | Topics |
|---|---|
| Logic | Clock Problems |
| Logic | Calendar Problems |
| Logic | Figures & Patterns |
| Data Interpretation | Tabular Data |
| Data Interpretation | Caselet & Web DI |
| Data Interpretation | Missing DI |
| Charts | Bar & Line Graphs |
| Charts | Pie Charts |
| Charts | Scatter Diagrams |
| Charts | Histograms |

## How It Works

1. **Learn:** Select a topic and review its concepts, formulas, worked examples, and strategy tips.
2. **Solve:** Enter your own values into the available calculator to work through a problem. Data-related topics may include visual charts.
3. **Practice:** Answer topic-specific multiple-choice questions and receive feedback.
4. **Track progress:** Earn XP for correct answers and monitor accuracy and streaks on the Progress page.

### Scoring

- Each correct answer awards **10 XP**.
- Correct answers extend the current streak.
- An incorrect answer resets the current streak.
- Accuracy and performance are tracked overall and by topic.
- Progress is saved in the browser and can be reset from the Progress page.

## Technology Stack

- **HTML** — page structure
- **CSS** — layout, styling, and responsive design
- **JavaScript** — navigation, topic interactions, calculations, quiz logic, scoring, and progress tracking
- **Browser storage** — saves progress locally in the user's browser

LogicIQ is implemented as a self-contained web application and does not require a separate backend or database for its current features.

## Getting Started

### Requirements

- A modern web browser such as Chrome, Firefox, Safari, or Edge
- The project HTML file

### Run Locally

1. Download or clone this repository.
2. Locate the main HTML file (for example, `logiciq.html`).
3. Open the file in a modern web browser.
4. Use the navigation bar to access Home, Learn, Practice, Formulas, Progress, and the Topics menu.

No package installation or build step is required for the current standalone version.

## Project Structure

A simple project setup may look like this:

```text
LogicIQ/
├── logiciq.html
├── README.md
└── screenshots/
    ├── home.png
    ├── practice.png
    └── progress.png
```

The HTML filename and screenshot folder should match the actual names used in your repository.

## Current Limitations

- Each topic currently has a small question set, so questions may repeat.
- The pattern solver supports only simple rules, such as addition, multiplication, and constant second differences.
- Progress is stored in the current browser and does not automatically synchronize across devices.
- Calculators and quizzes should be tested with different inputs before final deployment.

## Future Enhancements

- Timed quiz mode
- Larger question bank and difficulty levels
- More detailed, step-by-step solver explanations
- Daily challenge and practice reminders
- User accounts and cloud-synchronized progress

## Academic Project

**Project:** LogicIQ — Logic & Data Interpretation System for Competitive Exam Preparation  
**Course:** Logic and Data Interpretation – II (OE-II)  
**Department:** Artificial Intelligence & Data Science  
**Institution:** A. C. Patil College of Engineering, Navi Mumbai

## Live Demo

[Open LogicIQ on Claude Artifacts](https://claude.ai/artifact/Y4DnDvxDn9yenuv7JaNuHi)

---

LogicIQ makes aptitude practice more structured by bringing concept learning, problem solving, quizzes, and progress tracking together in one place.
