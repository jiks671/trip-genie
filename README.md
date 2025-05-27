# 🧞‍♂️ Trip Genie

An AI-powered travel planning application that helps users create personalized travel itineraries, manage bookings, and get real-time travel assistance.

## 🌟 Features

- Smart Itinerary Generator with AI-powered recommendations
- Personalized travel planning based on preferences
- Real-time flight and hotel search
- Budget planning and tracking
- Local AI Concierge for real-time assistance
- Multi-city trip planning
- Travel buddy matching
- Expense tracking and bill splitting
- AI-generated travel journals

## 🏗️ Tech Stack

- **Mobile App**: React Native
- **Backend**: Node.js + Express
- **Database**: MongoDB/Supabase
- **AI Integration**: GPT-4
- **Real-time Features**: Firebase
- **APIs**: Skyscanner, Booking.com, Google Places, etc.

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- React Native development environment setup
- MongoDB or Supabase account
- API keys for various services

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/trip-genie.git
cd trip-genie
```

2. Install dependencies for mobile app:
```bash
cd mobile
npm install
```

3. Install dependencies for backend:
```bash
cd ../backend
npm install
```

4. Set up environment variables:
```bash
# In mobile directory
cp .env.example .env

# In backend directory
cp .env.example .env
```

5. Start the development servers:

```bash
# Start backend server
cd backend
npm run dev

# Start mobile app
cd ../mobile
npm run android # or npm run ios
```

## 📚 Documentation

- [Build Plan](docs/BUILD_PLAN.md)
- [Project Structure](docs/PROJECT_STRUCTURE.md)
- [API Documentation](docs/API.md)
- [Deployment Guide](docs/DEPLOYMENT.md)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

- Project Lead: [Your Name]
- Backend Developer: [Name]
- Frontend Developer: [Name]
- UI/UX Designer: [Name]

## 🙏 Acknowledgments

- OpenAI for GPT-4 integration
- Skyscanner for flight data
- Booking.com for hotel data
- Google Places API for local data 