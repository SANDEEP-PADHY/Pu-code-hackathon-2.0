# Pu-code-hackathon-2.0
# Urban Mobility Platform

## Team: Awks

### Hackathon Problem Statement
**Resolving Urban Gridlock - Innovation for City Mobility**

---

## Project Overview
The Urban Mobility Platform is a web application designed to address urban traffic congestion by providing users with efficient, safe, and eco-friendly mobility solutions. It integrates real-time data, ride-sharing, and green technology to revolutionize city transportation.

### Key Features
- **Ride Booking**: Users can book rides by specifying pickup and drop-off locations.
- **Real-Time Traffic Insights**: Live updates on traffic conditions and suggested alternative routes.
- **Ride-Sharing Matchmaking**: Options to share rides with others heading in the same direction.
- **Green Route Recommendations**: Highlighting the most eco-friendly routes.
- **Safety Features**: Includes a panic button and real-time ride tracking.
- **CO2 Emissions Tracking**: Displays the environmental impact of each ride.
- **Cost Estimation**: Provides a detailed cost breakdown for each ride.

---

## Website Structure
1. **Home Page**
   - Quick navigation to ride booking, traffic insights, and safety features.
2. **Ride Booking Page**
   - Interactive map and ride options with preferences.
3. **Traffic Insights Page**
   - Real-time traffic visualization and alternative routes.
4. **Safety Features Page**
   - Panic button and location sharing.
5. **User Profile Page**
   - Personal details, ride history, and stats.

---

## Technologies Used

### Frontend
- **React.js**: For building dynamic user interfaces.
- **Tailwind CSS**: For modern, responsive styling.
- **Google Maps API**: For geolocation and mapping functionalities.

### Backend
- **Node.js**: Backend server handling.
- **Express.js**: RESTful APIs and routing.
- **MongoDB**: Database for user and ride data.
- **Firebase/Socket.io**: Real-time tracking and notifications.

### Additional Tools
- **Twilio API**: For sending SMS notifications during emergencies.
- **Stripe API**: For seamless payment integration.

---

## Installation and Setup

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- API keys for Google Maps, Twilio, and Stripe

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/urban-mobility-platform.git
   ```
2. Navigate to the project directory:
   ```bash
   cd urban-mobility-platform
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```env
     PORT=3000
     MONGO_URI=your-mongodb-uri
     GOOGLE_MAPS_API_KEY=your-google-maps-api-key
     TWILIO_SID=your-twilio-sid
     TWILIO_AUTH_TOKEN=your-twilio-auth-token
     STRIPE_SECRET_KEY=your-stripe-secret-key
     ```
5. Start the development server:
   ```bash
   npm start
   ```
6. Open the application in your browser:
   ```
   http://localhost:3000
   ```

---

## Project Modules
1. **Authentication**
   - User login and registration.
2. **Ride Booking**
   - Fetch and display ride options.
3. **Traffic Insights**
   - Display traffic data and route suggestions.
4. **Safety Features**
   - Panic button and emergency contact notifications.
5. **Payment Integration**
   - Cost calculation and payment processing.
6. **Admin Dashboard (Optional)**
   - Monitor platform usage and manage data.

---

## Future Enhancements
- Integration with autonomous vehicle services.
- Multi-modal transport suggestions (combining ridesharing and public transport).
- AI-based route optimization for lower CO2 emissions.

---

## Contributors
- **[Your Name]** - Project Lead
- **[Team Member Names]** - Roles and responsibilities

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments
We thank the hackathon organizers and mentors for their support and guidance.
