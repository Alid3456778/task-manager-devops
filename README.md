# Task Manager - DevOps Learning Project

A full-stack Task Manager application built for learning DevOps concepts and practices.

## 🚀 Features

- **Full CRUD Operations**: Create, Read, Update, Delete tasks
- **Priority Levels**: Low, Medium, High priority tasks
- **Task Completion**: Mark tasks as complete/incomplete
- **Statistics Dashboard**: Track total, completed, and pending tasks
- **Responsive Design**: Works on desktop and mobile
- **Health Check Endpoint**: `/health` for monitoring

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Environment**: dotenv for configuration

## 📦 Project Structure

```
task-manager-devops/
├── package.json          # Dependencies and scripts
├── server.js             # Main server file
├── .env.example          # Environment variables template
├── .gitignore            # Git ignore rules
├── README.md             # This file
└── public/
    └── index.html        # Frontend application
```

## 🔧 Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local installation or MongoDB Atlas)
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd task-manager-devops
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your MongoDB connection string
   ```

4. **Start MongoDB** (if using local installation)
   ```bash
   mongod
   ```

5. **Run the application**
   ```bash
   # Development mode (with auto-restart)
   npm run dev

   # Production mode
   npm start
   ```

6. **Access the application**
   - Open your browser to `http://localhost:3000`
   - Health check: `http://localhost:3000/health`

## 🔍 API Endpoints

- `GET /api/tasks` - Get all tasks
- `POST /api/tasks` - Create a new task
- `PUT /api/tasks/:id` - Update a task
- `DELETE /api/tasks/:id` - Delete a task
- `GET /health` - Health check endpoint

## 📊 Health Check Response

```json
{
  "status": "OK",
  "timestamp": "2024-01-15T10:30:00.000Z",
  "uptime": 3600,
  "environment": "development"
}
```

## 🧪 Testing

Currently, this project is set up for manual testing. In the DevOps journey, we'll add:
- Unit tests
- Integration tests
- End-to-end tests
- Test automation in CI/CD pipeline

## 🚀 DevOps Journey

This project will be used to learn:

1. **Version Control**: Git & GitHub
2. **CI/CD**: GitHub Actions or Jenkins
3. **Containerization**: Docker & Docker Compose
4. **Orchestration**: Kubernetes basics
5. **Deployment**: Cloud platforms (AWS, Heroku, etc.)
6. **Monitoring**: Logging and monitoring tools
7. **Best Practices**: Security, performance, automation

## 🤝 Contributing

This is a learning project. Feel free to:
- Add features
- Improve code quality
- Fix bugs
- Enhance documentation

## 📝 License

MIT License - feel free to use this for learning purposes.

## 🎯 Next Steps

1. Initialize Git repository
2. Set up GitHub repository
3. Create first commit
4. Set up CI/CD pipeline
5. Containerize with Docker
6. Deploy to cloud platform

---

**Happy Learning! 🎉**