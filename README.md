# Digital Clock and Calendar

This project is a simple, responsive digital clock and calendar implemented in HTML, CSS, and JavaScript. It is designed to adjust its layout dynamically based on screen orientation and size, providing an optimized user experience for both desktop and mobile devices.

## Features

### Clock
- Displays the current time in `HH:MM` format.
- Includes a blinking colon animation to represent seconds.

### Calendar
- Shows the current month and year.
- Highlights the current date.
- Includes buttons to navigate between months.
- Allows clicking on the month or year to reset to the current month.
- Maintains a consistent design for varying month names and day counts.

### Responsiveness
- Automatically switches between horizontal and vertical layouts based on screen orientation and dimensions.
- Adapts to different screen sizes, ensuring usability on both desktop and mobile devices.

## Usage

### Running Locally
1. Clone the repository or download the `index.html` file.
2. Open the file in any modern web browser.

### Deployment
You can upload the `index.html` file to any web hosting platform or use GitHub Pages to host it.

## File Structure
- **index.html**: The main HTML file containing the structure, styles, and JavaScript for the clock and calendar.

## How It Works
- The time is updated every second using `setInterval`.
- The calendar dynamically adjusts the days based on the selected month and year.
- CSS media queries ensure the layout adapts to screen size and orientation.
- JavaScript handles calendar navigation and resets.

## Future Improvements
- Add support for localization and different time zones.
- Enhance the design with additional themes.
- Implement week start customization (e.g., Monday or Sunday).

## License
This project is open-source and available under the [MIT License](LICENSE).

