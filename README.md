# 💬 Chatty - Real-time Chat Application

<div align="center">
  <img src="https://images.unsplash.com/photo-1611606063065-ee7946f0787a?w=800&auto=format&fit=crop&q=80" alt="Chat App Banner" width="800"/>
</div>

## ✨ Features

- 🔐 User authentication (Sign up, Sign in, Sign out)
- 👤 User profiles with avatar support
- 💭 Real-time messaging
- 🌅 Image sharing in chats
- 🎨 Multiple theme options
- 👥 Online user status
- 📱 Responsive design
- ⚡ Fast and reliable Socket.IO connection

## 🛠️ Tech Stack

- **Frontend**:
  - React with Vite
  - Tailwind CSS & DaisyUI
  - Zustand for state management
  - Socket.IO client
  - Axios for API calls

- **Backend**:
  - Node.js & Express
  - MongoDB & Mongoose
  - Socket.IO for real-time communication
  - JWT for authentication
  - Cloudinary for image storage

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- Cloudinary account

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/chatty.git
cd chatty
```

2. Install dependencies
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Set up environment variables
```bash
# Backend .env
PORT=5001
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

4. Run the application
```bash
# Run backend
cd backend
npm run dev

# Run frontend in another terminal
cd frontend
npm run dev
```

## 📸 Screenshots

<div align="center">
  <img src="https://images.unsplash.com/photo-1607799279861-4dd421887fb3?w=400&auto=format&fit=crop&q=80" alt="Login Page" width="400"/>
  <img src="https://images.unsplash.com/photo-1611532736637-13a8bdf96508?w=400&auto=format&fit=crop&q=80" alt="Chat Interface" width="400"/>
</div>

## 🌈 Theme Customization

Chatty offers multiple themes powered by DaisyUI. You can customize the appearance by selecting from various pre-built themes including:
- 🌞 Light
- 🌙 Dark
- ☕ Coffee
- 🌸 Cupcake
- And many more!

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to check out our [Contributing Guide](CONTRIBUTING.md).

## 💖 Acknowledgments

- [Unsplash](https://unsplash.com) for the beautiful images
- [DaisyUI](https://daisyui.com/) for the awesome UI components
- [Socket.IO](https://socket.io/) for real-time functionality
- All our contributors and supporters

---

<div align="center">
  Made with ❤️ by Jay
</div>
