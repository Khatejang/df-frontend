# 🎬 Deepfake Frontend Application 🤖

## 📝 Overview

A cutting-edge React-based frontend application for our deepfake project, crafted with modern web technologies to deliver an intuitive and powerful user experience.

## 🚀 Technologies

[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![Mantine](https://img.shields.io/badge/Mantine-339AF0?style=for-the-badge&logo=mantine&logoColor=white)](https://mantine.dev/)
[![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)](https://reactrouter.com/)
[![Zustand](https://img.shields.io/badge/Zustand-764ABC?style=for-the-badge&logo=react&logoColor=white)](https://zustand-demo.pmnd.rs/)
[![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)](https://axios-http.com/)

## ✨ Features

- 📱 Responsive UI
- 🔀 Seamless client-side routing
- 🧩 Modular React architecture
- 🌐 Efficient state management with Zustand
- 🚀 Streamlined API communications using Axios

## 📦 Prerequisites

### 1. Required Software

- [NPM](https://nodejs.org/en/download)

### 2. Configuration and Connectivity Setup

#### ✅ Critical Configuration Checklist

| Configuration            | File / Location | Action Required                                             |
| ------------------------ | --------------- | ----------------------------------------------------------- |
| **Base URL**             | `axios.js`      | ✅ Set the correct backend API endpoint                     |
| **Backend Connectivity** | `df-backend`    | 🔗 Ensure complete integration and successful communication |

#### ⚠️ Common Pitfalls

Misconfiguration can lead to:

- API connection failures
- Data synchronization issues

#### 💡 Best Practices

- Double-check all endpoint URLs
- Test all connections in a staging environment before production
- Avoid hardcoding sensitive data; use the designated configuration files

## 🏗️ Project Architecture

```
df-frontend/
├── src/
│   ├── assets/                 # Static assets like images, svgs
│   ├── components/             # Reusable React components
│   ├── global/                 # Global Instances
│   ├── hooks/                  # React Hooks
│   ├── pages/                  # Page components
│   ├── plugins/                # Vue plugins configuration
│   ├── router/                 # Application routing
│   ├── store/                  # Zustand state management
│   ├── App.jsx                 # Root component
│   ├── App.module.css          # Root CSS Module
│   └── main.jsx                # Entry point
│   └── index.css               # Entry point CSS file
└── public/                     # Public static assets
```

## 📚 Dependencies Guide

| Documentation      | Link                              | Description                |
| ------------------ | --------------------------------- | -------------------------- |
| **Mantine 7**      | https://v7.mantine.dev/           | Vue 2 Documentation        |
| **Zustand**        | https://zustand-demo.pmnd.rs/     | Zustand Documentation      |
| **React Router 7** | https://reactrouter.com/          | React Router Documentation |
| **Axios**          | https://axios-http.com/docs/intro | Axios Documentation        |

## 💾 Project Setup

### Install Dependencies

```bash
npm install  # 📦 Installs all required node modules
```

### Available Commands

| Command         | Description                                      |
| --------------- | ------------------------------------------------ |
| `npm run dev`   | 🔧 Start in development mode with hot-reload     |
| `npm run build` | 📦 Build for production (minified and optimized) |
| `npm run lint`  | 🧹 Lint and fix code issues                      |

## 🔍 Troubleshooting Guide

### API Connection Issues

| Issue                       | Solution                                                     |
| --------------------------- | ------------------------------------------------------------ |
| API timeout errors          | Check network connectivity and backend server status         |
| CORS errors                 | Ensure backend has proper CORS configuration for your domain |
| Data synchronization issues | Check local storage quota and clear cache if necessary       |

## 📋 Commit Message Guidelines

Use the following emojis to indicate the nature of your commits:

| Emoji | Code                          | Description                       |
| ----- | ----------------------------- | --------------------------------- |
| 💯    | `:100:`                       | Full functionality implementation |
| 🔧    | `:wrench:`                    | Code improvement / refactor       |
| 🐛    | `:bug:`                       | Bug fix                           |
| 📑    | `:bookmark_tabs:`             | Documentation and comments        |
| ☕    | `:coffee:`                    | Minor or initial changes          |
| 🚧    | `:construction:`              | Work in progress                  |
| 🗑️    | `:wastebasket:`               | Code or file deletion             |
| 📓    | `:notebook:`                  | README updates                    |
| ✏️    | `:pencil2:`                   | Typo or naming corrections        |
| ♻️    | `:recycle:`                   | Code refactoring                  |
| 🔀    | `:twisted_rightwards_arrows:` | Branch merge                      |
| ⏪    | `:rewind:`                    | Reverting changes                 |
| 📱    | `:iphone:`                    | Responsive design changes         |
| 📌    | `:pushpin:`                   | Hotfixes                          |

## 🤝 Contributing Guidelines

### Branch Naming

- `developer`: For main development
- `feature/feature-name`: For new features
- `hotfix/issue-name`: For critical fixes
- `release/version`: For release preparation

### Code Style

- Follow Reactjs style guide
- Use ESLint configuration
- Write meaningful comments

## 🔒 Security Considerations

- All API requests must use HTTPS
- Sensitive data must be encrypted at rest and in transit
- Implement proper input validation to prevent injection attacks
- Regular security audits are conducted on the codebase

> For security issues, please contact the security team at `spcf.ictdu@spcf.edu.ph`.

## 👥 Development Team

- 👨‍💻 **Gabriel Alfonso M. Gatbonton** - Senior Frontend Developer
- 👨‍💻 **Rhymeses E. Cortez** - Junior Frontend Developer
- 👨‍💻 **John Carlo D. Paz** - Junior Frontend Developer
- 👨‍💻 **Jose Gabriel B. Cruz** - Junior Frontend Developer
- 👨‍💻 **Marjorie Khate C. Aguarin** - Junior Frontend Developer
