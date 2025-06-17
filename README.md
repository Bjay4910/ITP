# Intelligent Travel Planner (ITP)

A comprehensive web application designed to help users plan their trips intelligently with integrated services for flights, weather, currency conversion, and location-based recommendations.

## Features

### 🗺️ Trip Planning
- Interactive trip planning interface
- Multi-destination support
- Itinerary optimization
- Custom trip preferences

### ✈️ Integrated Services
- **Flight Search**: Find and compare flight options
- **Weather Forecast**: Real-time weather information for destinations
- **Currency Converter**: Live exchange rates for budget planning
- **Location Services**: Google Maps integration for route planning
- **Recommendations**: TripAdvisor integration for attractions and reviews

### 👤 User Management
- User authentication and registration
- Personal trip history
- Saved trip preferences
- Account management

### 📱 Modern Interface
- Responsive design for all devices
- Bootstrap-powered UI components
- Intuitive navigation
- Real-time updates

## Tech Stack

- **Frontend**: React 18, Bootstrap 5
- **Styling**: CSS3, Bootstrap Icons
- **Routing**: React Router DOM
- **APIs**: Google Maps, Weather API, Currency API, TripAdvisor API
- **Deployment**: GitHub Pages

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Bjay4910/ITP.git
cd ITP
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open your browser and navigate to `http://localhost:3000`

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm run build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm run deploy` - Deploys the app to GitHub Pages

## Project Structure

```
ITP/
├── public/
│   ├── images/
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── api/
│   │   ├── currencyService.js
│   │   ├── flightService.js
│   │   ├── googleMapsService.js
│   │   ├── tripAdvisorService.js
│   │   └── weatherService.js
│   ├── components/
│   │   ├── Footer.js
│   │   └── Navigation.js
│   ├── context/
│   │   └── AuthContext.js
│   ├── pages/
│   │   ├── DashboardPage.js
│   │   ├── HomePage.js
│   │   ├── LoginPage.js
│   │   ├── PlanTripPage.js
│   │   └── [other pages]
│   ├── utils/
│   │   └── itineraryOptimizer.js
│   ├── App.js
│   ├── index.js
│   └── index.css
└── package.json
```

## API Integration

The application integrates with several external APIs:

- **Google Maps API**: For location services and route planning
- **Weather API**: For destination weather forecasts
- **Currency Exchange API**: For real-time currency conversion
- **TripAdvisor API**: For attraction recommendations and reviews

## Deployment

The application is deployed using GitHub Pages. To deploy:

```bash
npm run deploy
```

This will build the project and deploy it to the `gh-pages` branch.

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License.

## Contact

King James - jamesgyampoh560@gmail.com

Project Link: [https://github.com/Bjay4910/ITP](https://github.com/Bjay4910/ITP)

Live Demo: [https://bjay4910.github.io/ITP](https://bjay4910.github.io/ITP)