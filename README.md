# Modern URL Shortener

A full-stack URL shortening application built with React.js, featuring a modern UI, authentication, and comprehensive analytics for each shortened URL.

## ✨ Features

- 🔐 Secure user authentication
- 🔗 URL shortening with custom aliases
- 📊 Advanced analytics dashboard
  - Click tracking
  - Location-based statistics
  - Interactive graphs and charts
- 📱 Responsive design
- 📈 Real-time statistics
- 🔄 QR code generation
- 🛡️ Protected routes
- 📊 Visual data representation
  - Pie charts for location data
  - Click statistics graphs

## 🛠️ Technology Stack

### Frontend
- React.js
- Tailwind CSS
- Shadcn UI Components
- Custom Hooks
- Context API for state management

### Backend
- Supabase
  - Authentication
  - Database
  - Real-time subscriptions
- RESTful APIs

### Deployment
- Hostinger

## 📋 Key Components

1. **Authentication System**
   - User registration
   - Login functionality
   - Protected routes
   - Row level security

2. **URL Management**
   - URL shortening
   - Custom alias support
   - QR code generation
   - URL deletion

3. **Analytics Dashboard**
   - Click tracking
   - Geographic data
   - Interactive charts
   - Real-time statistics

## 🚀 Getting Started

1. Clone the repository
```bash
git clone https://github.com/yourusername/url-shortener.git
cd url-shortener
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
```bash
cp .env.example .env.local
```

4. Configure Supabase
```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_key
```

5. Start the development server
```bash
npm run dev
```


## 🔒 API Endpoints

### Authentication
- `POST /api/auth/signup` - User registration
- `POST /api/auth/login` - User login

### URL Operations
- `POST /api/urls` - Create short URL
- `GET /api/urls` - Get user's URLs
- `DELETE /api/urls/:id` - Delete URL
- `GET /api/urls/stats` - Get URL statistics

## 🎯 Features Implementation

1. **Authentication Flow**
   - Implement user signup/login
   - Create protected routes
   - Add row-level security

2. **URL Management**
   - URL shortening logic
   - Custom alias handling
   - QR code generation

3. **Analytics**
   - Click tracking implementation
   - Geographic data collection
   - Statistical analysis

## 📈 Performance Optimization

- Implemented custom hooks for data fetching
- Used Context API for efficient state management
- Optimized database queries
- Implemented proper error handling

## 🚀 Deployment

1. Build the application
```bash
npm run build
```

2. Deploy to Hostinger
- Configure deployment settings
- Set up environment variables
- Deploy the application

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request


## 🙏 Acknowledgments

- Shadcn UI for components
- Supabase for backend services
- React community
- Tailwind CSS team