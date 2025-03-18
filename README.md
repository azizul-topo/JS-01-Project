

# Daily Mood Tracker

## Introduction

This **Daily Mood Tracker** is a web-based application designed to allow users to log their moods daily using an easy-to-use calendar interface. The app provides a simple and intuitive way to track daily emotional well-being and gain insights into mood trends over time. It stores data locally on the user's browser, allowing the moods to persist even if the page is refreshed.

The application features:
- **Emoji-based mood logging** (Happy, Sad, Neutral, Excited, Angry).
- A **calendar layout** where each day is clickable to log moods.
- **Month navigation** to track moods for different months and years (2024-2025).
- **Local storage** to save mood entries without requiring a backend server.

## Features

- **Calendar View:** Displays a monthly view where each day of the month is shown in a grid format. Each date is clickable to log the mood for that day.
  
- **Mood Logging:** When a user clicks on a specific day, an input form appears with various mood options (Happy, Sad, Neutral, Excited, Angry) to select. The mood is logged as an emoji on the selected date.

- **Data Persistence:** Moods are stored in the browser’s **localStorage**, ensuring data persists even if the page is reloaded or revisited.

- **Month Navigation:** The user can navigate between months and years (2024-2025), with proper alignment of days to weekdays.

- **No Backend:** Everything is stored locally on the user's browser using **localStorage**, which makes this app fast and lightweight.

## How to Use

1. **Choose a Mood:** Click on any day in the calendar. You will be prompted to select your mood for that day.
  
2. **Select Mood:** Choose from the mood options (Happy, Sad, Neutral, Excited, or Angry), and the emoji corresponding to your mood will be saved for that day.

3. **View Mood History:** Your selected moods will appear under each respective date. You can navigate through months using the "Prev" and "Next" buttons.

4. **Data Persistence:** Once a mood is logged, it will remain saved and visible across page refreshes until manually cleared from **localStorage**.

## Technologies Used

- **HTML:** Structure and layout of the web page.
- **CSS:** Styling and layout adjustments for a responsive and clean UI.
- **JavaScript:** Handling of logic for mood tracking, calendar generation, and localStorage.

## How to Run the Project

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate into the project directory:
   ```bash
   cd daily-mood-tracker
   ```

3. Open the `index.html` file in your preferred web browser:
   ```bash
   open index.html
   ```

4. The app should now be running in your browser. You can log your moods by selecting days on the calendar.

## Future Improvements

While this app provides basic functionality for mood tracking, future versions could include:
- **Mood Trends:** Visual graphs to track mood patterns over weeks or months.
- **User Accounts:** Integration of a backend for users to create accounts and sync their mood data across devices.
- **Notifications:** Reminders to log moods daily.
- **Multiple Moods per Day:** Allow users to log multiple moods on the same day if needed.

## License

This project is open-source and available under the MIT License. Feel free to contribute, modify, and share it.

