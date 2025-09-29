# SeniorCare Connect

A comprehensive web application designed to help seniors manage their healthcare appointments, therapy sessions, and nursing care with ease. This demo showcases a modern, accessible interface for booking and managing healthcare services.

## Features

### 🏠 Dashboard
- Personalized welcome screen with user-specific information
- Quick access to upcoming appointments
- Service overview and package details
- Special offers and promotions
- Health tracking and resource access

### 📅 Booking System
- **Service Selection**: Choose from nursing care, therapy, occupational therapy, mental health support, and specialist visits
- **Date & Time Selection**: Interactive calendar for appointment scheduling
- **Location Selection**: Choose between patient's room, clinic, or home visits
- **Staff Selection**: Option to request specific healthcare providers
- **Equipment Rental**: Add medical equipment like wheelchairs, crutches, and walkers
- **Multi-Service Booking**: Book multiple services in a single session

### 👤 User Management
- User profile management
- Appointment history and tracking
- Package and subscription details
- Notification preferences

### 💬 Communication
- Built-in chat system for healthcare provider communication
- Notification system for appointment reminders and updates

### 📊 Health Tracking
- Wellness monitoring dashboard
- Health resource library
- Progress tracking capabilities

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Tailwind CSS with custom configuration
- **Icons**: Material Symbols (Google Icons)
- **Fonts**: Lexend font family for accessibility
- **Responsive Design**: Mobile-first approach with dark mode support

## Project Structure

```
├── index.html              # Landing page
├── dashboard.html          # Main dashboard
├── profile.html           # User profile management
├── chat.html              # Communication interface
├── notification.html      # Notification center
├── wellness-tracking.html # Health monitoring
├── health-resource.html   # Health information library
├── package-detail.html    # Subscription details
├── view-all-bookings.html # Appointment history
└── booking/               # Booking flow pages
    ├── service-select.html    # Service selection
    ├── booking.html          # Main booking interface
    ├── select-date.html      # Date selection
    ├── select-location.html  # Location selection
    ├── select-staff.html     # Staff selection
    ├── staff-detail.html     # Staff information
    ├── add-service.html      # Add additional services
    ├── summary.html          # Booking summary
    └── confirm.html          # Booking confirmation
```

## Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd senior-care-connect-app-demo
   ```

2. **Open the application**
   - Open `index.html` in your web browser
   - Or serve the files using a local web server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. **Navigate the application**
   - Start at the landing page (`index.html`)
   - Click "Get Started" to access the dashboard
   - Explore the booking system and other features

## Design Features

### Accessibility
- High contrast color schemes
- Readable Lexend font family
- Large touch targets for mobile devices
- Semantic HTML structure
- Screen reader friendly navigation

### Responsive Design
- Mobile-first responsive layout
- Adaptive navigation with bottom tab bar
- Touch-friendly interface elements
- Optimized for various screen sizes

### Dark Mode Support
- Automatic dark mode detection
- Consistent theming across all pages
- Reduced eye strain for extended use

## Color Scheme

- **Primary**: `#38e07b` (Green) - Used for primary actions and highlights
- **Background Light**: `#f6f8f7` - Light mode background
- **Background Dark**: `#122017` - Dark mode background
- **Secondary Colors**: Various blues, purples, and teals for different service categories

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Responsive design works on tablets and desktop

## Contributing

This is a demo application showcasing senior care management features. For production use, consider:

- Adding backend API integration
- Implementing user authentication
- Adding real-time notifications
- Integrating with healthcare provider systems
- Adding data persistence
- Implementing security measures

## License

This project is a demonstration application. Please check with the repository owner for licensing information.

## Contact

For questions about this demo application, please refer to the project documentation or contact the development team.