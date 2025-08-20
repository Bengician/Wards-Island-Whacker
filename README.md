# 🎾 Ward's Island Whacker

This is my take on a tennis shot tracking app. Instead of tracking every shot in a rally, I've designed it to track the major shots in tennis that can be easily controlled and repeated by beginner and intermediate players. Specifically, the app is used to track serve, serve returns, and baseline rally shots. The purpose of this is to provide actionable recommendations for players who want to improve these fundamental tennis strokes.

## Features

* **Match and Point Tracking:** Start a new match, advance to a new point, and keep track of each shot within the point.

* **Configurable Data Points:** Log key variables for each shot, including:

  * Player

  * Test Condition (e.g., Serve, Baseline, Return)

  * Tempo (e.g., Light, Medium, Hard)

  * Stroke (e.g., Forehand, Backhand, Serve)

  * Outcome (Win or Lose)

* **Interactive Court:** Click on a visual representation of a tennis court to record the exact location of a shot.

* **Real-time Data Display:** All recorded shots are displayed in a dynamic table, updating in real-time as you log data.

* **CSV Export:** Easily export your collected data to a CSV file for analysis in spreadsheet applications like Microsoft Excel or Google Sheets.

* **Responsive Design:** The interface is optimized for use on both desktop and mobile devices.

## How to Use

1. **Start a New Match:** Click the "New Match" button to enter the names for the match and the two players. This will clear any previous data and start a new session.

2. **Log a Shot:**

   * Select the **Player** who hit the shot.

   * Select the **Test Condition**, **Tempo**, **Stroke**, and **Outcome** from the available options.

   * Click on the court diagram to mark the **Shot Location**.

   * Click **ENTER** to log the shot and move to the next hit.

3. **Advance Points:** Click the "New Point" button to increment the point count. The "Hit" counter will reset to 1.

4. **Export Data:** When you are finished, click the "Export to CSV" button to download a file containing all your logged data.

## Technologies Used

* **HTML5:** The core structure of the web page.

* **CSS3:** For styling, including a responsive and modern layout.

* **JavaScript (ES6+):** For all application logic, including event handling, data management, and CSV generation.

## Contributing

This project is a great example of a simple, useful tool built with just HTML, CSS, and JavaScript. Feel free to fork the repository, make improvements, and submit pull requests.
