# React Stopwatch

A simple, user-friendly stopwatch application built with React. This application provides basic timing functionality including start, stop, and reset capabilities with a clean interface.

## Features

- Start/Stop functionality
- Reset timer
- Display of minutes, seconds, and milliseconds
- Clean and intuitive user interface

## Technologies Used

- React.js
- useState, useEffect, and useRef hooks
- JavaScript timing functions

## Installation

To run this project locally, follow these steps:

1. Clone the repository or download the source code
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory
   ```
   cd StopWatch-Project
   ```

3. Install dependencies
   ```
   npm install
   ```

4. Start the development server
   ```
   npm start
   ```

5. Open your browser and visit `http://localhost:3000`

## Usage

- Click the **start** button to begin the stopwatch
- Click the **stop** button to pause the stopwatch
- Click the **reset** button to reset the stopwatch to 00:00:00

## How It Works

The stopwatch uses React's state management and effect hooks to track elapsed time. It calculates the difference between the current time and the start time, updating the display every 10 milliseconds when running.

## Demo

[Live Demo](https://stop-watch-project-chi.vercel.app/)

## License

MIT
