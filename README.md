<div align="center">
  <img src="public/logo.png" alt="TaskCore Logo" width="200"/>
  <h1>TaskCore</h1>
  <p><strong>A Modern Task Management Application for Students</strong></p>
  
  [![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
  [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
  [![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
  [![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
</div>

---

## 📋 About TaskCore

TaskCore is a student-focused productivity and task-management application designed to help students organize their academic workload efficiently. With an intuitive interface, smart notifications, and powerful task management features, TaskCore makes staying on top of your studies easier than ever.

## ✨ Features

### 🎯 Core Features
- **Task Management** - Create, edit, update, and delete tasks with ease
- **Priority Levels** - Organize tasks by High, Medium, or Low priority
- **Categories** - Sort tasks by subject (Mathematics, Science, English, History, Computer Science, etc.)
- **Due Dates** - Set deadlines and track upcoming tasks
- **Task Completion** - Mark tasks as complete with visual indicators
- **Search & Filter** - Find tasks quickly with powerful filtering options

### 📊 Dashboard
- **Real-time Statistics** - View total, completed, pending, and high-priority tasks
- **Upcoming Tasks** - Quick overview of your next tasks
- **Quick Actions** - Fast access to create tasks and view all tasks
- **Dynamic Date/Time** - Always know the current date and time
- **Interactive Cards** - Click on stat cards to navigate to tasks

### 🔔 Smart Notifications
- **Task Completion Alerts** - Get notified when you complete tasks
- **Reminder System** - Set custom reminders for important tasks
- **Notification Center** - View all your notifications in one place
- **Unread Indicators** - Never miss important updates

### 🎨 Modern UI/UX
- **Dark Mode** - Switch between light and dark themes
- **Mobile-First Design** - Fully responsive on all devices
- **Smooth Animations** - Delightful hover effects and transitions
- **Clean Interface** - Minimal, distraction-free design
- **Intuitive Navigation** - Easy-to-use sidebar and mobile header

### ⚙️ Settings & Customization
- **Profile Management** - Update your personal information
- **Theme Toggle** - Choose between light and dark mode
- **Notification Preferences** - Customize your notification settings

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Osaseye/TaskCore.git
   cd TaskCore/TASKCORE
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
```

The production-ready files will be in the `dist` folder.

## 🛠️ Tech Stack

- **Frontend Framework**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: TailwindCSS with custom design system
- **Routing**: React Router DOM
- **State Management**: React Context API
- **Storage**: LocalStorage for data persistence
- **Icons**: Custom SVG icon components
- **Deployment**: Vercel

## 📁 Project Structure

```
TASKCORE/
├── public/
│   ├── icon.png           # App favicon
│   └── logo.png           # App logo
├── src/
│   ├── assets/            # Static assets
│   ├── components/
│   │   ├── common/        # Reusable components (Button, Card, Badge, etc.)
│   │   ├── layout/        # Layout components (Sidebar, MobileHeader, etc.)
│   │   └── tasks/         # Task-specific components (CreateTaskModal, EditTaskModal)
│   ├── context/           # React Context providers
│   │   ├── TaskContext.tsx
│   │   ├── ThemeContext.tsx
│   │   └── NotificationContext.tsx
│   ├── hooks/             # Custom React hooks
│   ├── pages/             # Page components
│   │   ├── Dashboard.tsx
│   │   ├── Tasks.tsx
│   │   ├── Notifications.tsx
│   │   ├── Settings.tsx
│   │   ├── Login.tsx
│   │   └── Register.tsx
│   ├── types/             # TypeScript type definitions
│   ├── App.tsx            # Main app component
│   ├── main.tsx           # App entry point
│   └── index.css          # Global styles
├── index.html
├── package.json
├── tailwind.config.js     # Tailwind configuration
├── tsconfig.json          # TypeScript configuration
├── vite.config.ts         # Vite configuration
└── vercel.json            # Vercel deployment config
```

## 🎨 Design System

### Color Palette
- **Primary**: Navy Blue (#1E2A78)
- **Accent**: Sky Blue (#4A90E2)
- **Status Colors**:
  - Success: #22C55E
  - Warning: #F59E0B
  - Danger: #EF4444
- **Neutral**: Gray scale from #F9FAFB to #111827

### Typography
- **Font Family**: Inter (system fonts fallback)
- **Headings**: Bold, Navy Blue
- **Body**: Regular, Neutral Dark

## 🔐 Features in Development

- [ ] User authentication and profiles
- [ ] Task collaboration and sharing
- [ ] Calendar integration
- [ ] Study timer / Pomodoro technique
- [ ] Task analytics and insights
- [ ] Cloud sync across devices
- [ ] Mobile app (React Native)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Osaseye**
- GitHub: [@Osaseye](https://github.com/Osaseye)

## 🙏 Acknowledgments

- Design inspired by modern productivity apps
- Icons designed using Heroicons principles
- Color palette based on educational design best practices

---

<div align="center">
  <p>Made with ❤️ for students everywhere</p>
  <p>⭐ Star this repo if you find it helpful!</p>
</div>

