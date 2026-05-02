# 🧠 Sentifi Pro: Behavioral Finance & Emotional ROI Engine

**Sentifi Pro** is a "Financial Therapist" web application built to detect high-risk emotional spending patterns and intervene using principles of Behavioral Economics. It's a Hackathon-grade prototype designed with a premium Glassmorphism UI and data-driven insights.

## ✨ Core Features

*   **Emotional ROI Logic:** Whenever you log an impulse or stress-induced spend, Sentifi calculates the 10-year **Opportunity Cost** at a 12% return. It shows you what that impulse buy is *actually* costing your future self.
*   **The Zen Score (Gamification):** A dynamic health meter (0-100) that tracks your spending behavior. Planned and happy purchases increase your score, while emotional and impulsive purchases trigger a drop.
*   **Pattern Recognition (Intervention Mode):** The AI tracks consecutive emotional spending. If you log 3 "Stressed" expenses in a row, the dashboard pulses red, and the AI pivots to intervention mode—suggesting a free alternative like taking a 10-minute walk.
*   **The 24-Hour Cooling Toggle:** A UI switch that asks you to "Commit to waiting 24 hours ⏱️" before buying. This introduces a psychological friction point to combat impulse buying.
*   **Deep Analytics Dashboard:**
    *   **Emotional Breakdown:** A doughnut chart visualizing your spending by mood.
    *   **Category Spending:** A bar chart showing where your money is going.
    *   **Daily Spending Trend:** A line chart tracking your expenses over the last 7 days.
*   **Premium UI/UX:** Built with Tailwind CSS, featuring a dark theme, glassmorphism cards, gradient accents, and smooth Chart.js animations.

## 🛠️ Tech Stack

*   **Backend:** Python, Flask, SQLite
*   **Frontend:** Vanilla JavaScript, HTML5
*   **Styling & UI:** Tailwind CSS (via CDN), Google Fonts (Inter)
*   **Data Visualization:** Chart.js

## 🚀 Getting Started

Follow these instructions to run the project locally.

### Prerequisites

You need Python 3 installed on your system. 

### Installation & Run

1. Clone or download this repository.
2. Open a terminal and navigate to the project directory:
   ```bash
   cd sentifi_project
   ```
3. Install the required dependencies:
   ```bash
   pip install Flask
   ```
4. Run the application:
   ```bash
   python app.py
   ```
5. Open your browser and go to:
   ```text
   http://127.0.0.1:5000
   ```

*Note: The database (`database.db`) is automatically generated with the necessary schema when you first run the app.*
