# 📱 Subscription Tracker

A modern web application to help you manage and track your subscriptions efficiently. Never miss a renewal or payment again!

## ✨ Features

- 🔐 Secure user authentication
- 📊 Track multiple subscriptions
- 🔔 Renewal notifications
- 💰 Payment tracking
- 📱 Responsive design
- 🔄 Real-time updates

## 🚀 Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT, bcrypt
- **Email Notifications**: Nodemailer
- **Task Scheduling**: Upstash QStash
- **Security**: Arcjet

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Prakharsahu10/subscription-tracker.git
   cd subscription-tracker
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your environment variables:

   ```env
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   EMAIL_USER=your_email
   EMAIL_PASS=your_email_password
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## 📝 API Endpoints

- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login user
- `GET /api/subscriptions` - Get all subscriptions
- `POST /api/subscriptions` - Create a new subscription
- `PUT /api/subscriptions/:id` - Update a subscription
- `DELETE /api/subscriptions/:id` - Delete a subscription

## 🔧 Development

- Run in development mode: `npm run dev`
- Run in production mode: `npm start`

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- Your Name - Initial work

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape this project
- Special thanks to the open-source community for their amazing tools and libraries
