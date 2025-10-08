RentIT - Car Rental Website
A modern, responsive car rental website built with HTML and CSS. RentIT provides a complete solution for browsing premium vehicles, checking availability across multiple Albanian cities, and submitting rental applications online.

Features
Responsive Design - Clean, modern interface optimized for all devices
Vehicle Catalog - Browse through 8 premium car brands with detailed specifications
Multi-City Availability - Check vehicle availability in Tirane, Durres, Elbasan, Shkoder, and Vlore
Detailed Specifications - View comprehensive technical details for each vehicle model
Application System - User-friendly rental application form
Multi-Language Support - Interface available in Albanian with language selector
Brand Showcase - Featured brands: Toyota, BMW, Mercedes-Benz, Audi, Porsche, Hyundai, Subaru, and Nissan
Project Structure
car-rental-website/
│
├── index.html          # Main entry point of the website
├── css/
│   ├── style.css       # Main stylesheet
│   └── responsive.css  # Media queries for responsive design
├── js/
│   ├── main.js         # Core JavaScript functionality
│   └── booking.js      # Booking system logic
├── images/
│   ├── cars/           # Vehicle images
│   ├── icons/          # UI icons
│   └── banners/        # Hero and promotional images
├── assets/
│   └── fonts/          # Custom fonts (if any)
└── README.md           # Project documentation
Getting Started
Prerequisites
No special prerequisites are required. You only need:

A modern web browser (Chrome, Firefox, Safari, Edge)
A text editor (VS Code, Sublime Text, etc.) for development
Installation
Clone the repository or download the project files:
bash
git clone https://github.com/yourusername/car-rental-website.git
Navigate to the project directory:
bash
cd car-rental-website
Open index.html in your web browser:
bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
Alternatively, you can use a local development server:

bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
Then visit http://localhost:8000 in your browser.

Usage
For Users
Browse Vehicles: Navigate through the homepage to view available cars
Select a Car: Click on any vehicle to view detailed specifications
Book a Rental: Fill out the booking form with your dates and information
Review: Check your booking details and total cost before confirming
For Developers
The main entry point is index.html, which includes:

Navigation header
Hero section with call-to-action
Vehicle showcase
Booking form
Footer with contact information




