# Movie Seat Booking Project

## Overview

Welcome to the Movie Seat Booking Project! This project is a frontend web application designed to simulate the process of selecting and booking seats for a movie. It is built entirely using HTML, CSS, and JavaScript, making it a great way to practice and demonstrate your skills in web development.

## Project Features

This project includes several key features that mimic a real-world movie seat booking experience:

1. **Interactive Seat Selection**: Users can select seats by clicking on available options in a visually designed theater layout.
2. **Real-Time Seat Availability**: The interface updates to show selected, available, and booked seats using different colors and styles.
3. **Dynamic Pricing Calculation**: The total price is automatically updated as users select or deselect seats.
4. **Responsive Design**: The layout adjusts to different screen sizes, ensuring a seamless experience on both desktop and mobile devices.

## Technologies Used

- **HTML**: For structuring the content and layout of the application.
- **CSS**: For styling the application, including the seat layout, buttons, and overall design.
- **JavaScript**: For adding interactivity, such as handling seat selection, updating the UI dynamically, and calculating the total cost.

## Getting Started

To get started with this project, simply clone the repository and open the `index.html` file in your web browser. This project does not require any backend setup or external libraries, making it easy to run on any local machine.

### Cloning the Repository

```bash
git clone https://github.com/your-username/movie-seat-booking.git
```

### Opening the Project

Navigate to the project folder and open `index.html` in your browser:

```bash
cd movie-seat-booking
open index.html
```

## Project Structure

Here's an overview of the project's file structure:

```
movie-seat-booking/
│
├── index.html        # The main HTML file
├── style.css         # The CSS file for styling the layout
└── script.js         # The JavaScript file for adding interactivity
```

### index.html

This file contains the basic structure of the page, including the movie selection dropdown, the seat layout, and the display for the total price and selected seats.

### style.css

This file defines the styles for the entire application. It includes the layout of the seats, color schemes for available, selected, and booked seats, and responsive design rules to ensure the application looks good on all devices.

### script.js

This is the main JavaScript file that adds interactivity to the application. It handles user actions like selecting seats, updating the UI, and calculating the total cost of the selected seats.

## How It Works

### Seat Layout

The seat layout is created using a grid system in HTML, styled with CSS. Each seat is represented by a clickable element that changes appearance based on its state (available, selected, or booked).

### Seat Selection

When a user clicks on a seat, the JavaScript code updates the class of the seat to reflect its new state. If the seat is available, it changes to selected, and the total cost is updated accordingly.

### Pricing Calculation

The total cost is dynamically calculated based on the number of seats selected and the price per seat. This information is displayed in real-time at the bottom of the page.

### Responsive Design

The application is designed to be fully responsive, with the layout adjusting to fit different screen sizes. This ensures a smooth user experience whether on a desktop, tablet, or mobile device.

## Customization

You can easily customize this project to suit different needs or preferences. For example, you can:

- Change the seat layout by modifying the HTML structure.
- Adjust the styles in the CSS file to match your desired color scheme.
- Add more functionality in the JavaScript file, such as implementing seat categories (e.g., VIP, regular).

## Future Enhancements

Here are some ideas for future enhancements to this project:

- **Local Storage Integration**: Save the user's seat selection so that it persists even after refreshing the page.
- **Seat Type Pricing**: Implement different pricing tiers for different seat types (e.g., VIP vs. regular seats).
- **Booking Confirmation**: Add a confirmation step before finalizing the seat booking.
- **Animations**: Enhance the user experience with subtle animations, such as seat selection transitions.

## Conclusion

This Movie Seat Booking Project is a simple yet effective way to practice your frontend web development skills. By focusing on HTML, CSS, and JavaScript, you can create a fully functional and interactive web application. Feel free to explore, modify, and expand upon this project to make it your own!

---

**Author**: [K.YUVA SHANKAR](https://www.linkedin.com/in/yuva-shankar-4ba786228?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
