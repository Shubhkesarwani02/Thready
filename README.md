# Thready

Modern social platform with real-time messaging and seamless interactions. Built with MERN stack.

## ⚡ Quick Start

```bash
# Clone & Install
git clone https://github.com/Shubhkesarwani02/Thready/
cd Thready
npm install
cd frontend && npm install

# Set environment variables
# Create .env in root with:
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

# Run
npm run dev        # Backend
cd frontend && npm run dev  # Frontend
```

## 🎯 Features

- Real-time chat (Socket.IO)
- Post sharing & interactions
- User auth & profiles
- Follow system
- Dark/Light mode
- Image uploads
- Responsive design

## 🛠️ Tech Stack

**Frontend:**
- React + Vite
- Chakra UI
- Recoil (State)
- Socket.IO Client

**Backend:**
- Node.js + Express
- MongoDB + Mongoose
- Socket.IO
- JWT Auth
- Cloudinary

## � Structure

```
backend/
  ├─ controllers/   # API logic
  ├─ models/        # DB schemas
  ├─ routes/        # Endpoints
  └─ socket/        # Real-time
frontend/
  └─ src/
     ├─ components/ # UI components
     ├─ pages/      # Routes
     └─ hooks/      # Custom hooks
```

## 💻 Development

1. Fork the repo
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open pull request

## 📝 License

ISC Licensed. See [LICENSE](LICENSE).
