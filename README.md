🎬 Marquee – Ticket Booking Manager
A modern, responsive Movie Ticket Booking Management System built using HTML, CSS, and JavaScript.
Marquee helps manage movies, showtimes, seat bookings, customers, and booking records through a simple dashboard interface.
✨ Features
📊 Dashboard
View total movies listed
View scheduled showtimes
Track booked seats
View confirmed booking revenue
Display upcoming showtimes
View recent bookings
🎞️ Movie Management
Add new movies
Enter movie title, genre, duration, rating, and synopsis
Display movies as attractive cards
Remove movies when required
🕐 Showtime Management
Schedule movie showtimes
Select screen number
Choose date and time
Set ticket price
View seat occupancy
Remove scheduled showtimes
🎟️ Ticket Booking
Select a movie showtime
Interactive seat selection
4 rows with 10 seats per row
Display available, selected, and booked seats
Enter customer name and phone number
Automatically calculate total ticket price
Confirm bookings instantly
📋 Booking Management
View all reservations
Search bookings by:
Customer name
Phone number
Movie name
Cancel confirmed bookings
Automatically release cancelled seats
🌓 Theme Support
Dark and light theme support
Responsive design for desktop and mobile devices
🛠️ Technologies Used
HTML5 – Structure
CSS3 – Styling and responsive layout
JavaScript – Application logic and interactivity
LocalStorage – Browser-based data persistence
Google Fonts – Inter and Bebas Neue
📁 Project Structure
Marquee-Ticket-Booking-Manager/
│
└── index.html
The complete application is contained in a single index.html file.
🚀 How to Run
Method 1 – Browser
Download or clone this repository.
Open index.html.
The application will run directly in your browser.
Method 2 – VS Code
Open the project folder in Visual Studio Code.
Open index.html.
Use Live Server to launch the application.
💾 Data Storage
The application uses the browser's LocalStorage to save movies, showtimes, and booking information.
Note: Data is stored locally in the browser and is not connected to a cloud database or external backend.
🎫 Seat Layout
The booking system provides:
Screen

A  1 2 3 4 5 6 7 8 9 10
B  1 2 3 4 5 6 7 8 9 10
C  1 2 3 4 5 6 7 8 9 10
D  1 2 3 4 5 6 7 8 9 10
Each showtime has 40 seats in total.
📱 Responsive Design
The interface adapts to different screen sizes, including:
💻 Desktop
📱 Mobile
📟 Tablet
The navigation changes to a mobile-friendly layout on smaller screens.
🔄 Booking Flow
Select Showtime
       ↓
Choose Seats
       ↓
Enter Customer Details
       ↓
Calculate Total
       ↓
Confirm Booking
       ↓
Seats Marked as Taken
       ↓
Booking Added to Records
🔐 Current Limitations
This is a frontend-only project.
No backend server
No online payment gateway
No user authentication
No real-time database
Data is stored only in the current browser
No real cinema/theatre API integration
🔮 Future Enhancements
Possible improvements include:
🔐 User authentication
🗄️ MySQL / MongoDB database
💳 Online payment integration
📧 Booking confirmation through email
📱 SMS notifications
🎫 Digital ticket generation
🧾 PDF ticket download
👤 Admin and customer login
☁️ Cloud-based data storage
📈 Advanced revenue and occupancy analytics