# 🌾 Sabana - Complete Issue Management System

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Frontend-blue)](https://saba-front-end.vercel.app/)
[![API Docs](https://img.shields.io/badge/📚_API-Documentation-green)](https://it22d-backend.onrender.com/swagger/)
[![Backend Demo](https://img.shields.io/badge/🔧_Backend-Web_Interface-orange)](https://it22d-backend.onrender.com/)

> **Full-stack issue management system** inspired by Taiga, built with modern web technologies and featuring both REST API and web interfaces.

## 🚀 Quick Links

| Component | Repository | Live Demo | Technology |
|-----------|------------|-----------|------------|
| **Frontend** | [SabanaFront](https://github.com/inkih04/SabanaFront) | [🌐 Live App](https://saba-front-end.vercel.app/) | Next.js + React |
| **Backend** | [SabanaBack](https://github.com/inkih04/SabanaBack) | [🔧 Web Interface](https://it22d-backend.onrender.com/) | Django + DRF |
| **API Docs** | Backend Repository | [📚 Swagger UI](https://it22d-backend.onrender.com/swagger/) | OpenAPI 3.0 |

> ⚠️ **Important Note**: The live demos may take **30-60 seconds** to respond on first access due to free hosting tiers (Vercel and Render). Subsequent requests will be faster. Please be patient during the initial load.

## 📋 Project Overview

**Sabana** is a comprehensive issue management system developed as a full-stack web application. The project demonstrates modern web development practices with a complete separation between frontend and backend, providing multiple ways to interact with the system.

### 🏗️ Architecture

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   Frontend      │    │   Backend       │    │   Database      │
│   (Next.js)     │◄──►│   (Django)      │◄──►│   (SQLite)      │
│                 │    │                 │    │                 │
│ • React UI      │    │ • REST API      │    │ • Issues        │
│ • Responsive    │    │ • Web Interface │    │ • Users         │
│ • SSR/SSG       │    │ • Authentication│    │ • Attachments   │
└─────────────────┘    └─────────────────┘    └─────────────────┘
```

### ✨ Key Features

#### 🎯 Issue Management
- **Create & Edit Issues**: Full CRUD operations with rich text support
- **Advanced Filtering**: Sort by status, priority, assignee, and creation date
- **File Attachments**: Upload and manage issue-related files
- **Status Tracking**: Complete issue lifecycle management

#### 🔐 Authentication Systems
- **Frontend**: Pre-defined user system (academic requirement)
- **Backend**: Google OAuth 2.0 integration for web interface
- **API**: Token-based authentication for REST endpoints

#### 📱 Multiple Interfaces
- **Modern SPA**: React-based frontend with Next.js
- **Traditional Web**: Server-rendered Django interface
- **REST API**: Complete programmatic access via API

## 🛠️ Technology Stack

### Frontend Technologies
- **Next.js 13+** - React framework with App Router
- **React 18** - Component-based UI library
- **JavaScript** - Modern ES6+ features
- **CSS** - Pure CSS with responsive design
- **Vercel** - Deployment and hosting

### Backend Technologies
- **Python 3.x** - Primary programming language
- **Django** - Web framework
- **Django REST Framework** - API development
- **SQLite** - Database
- **Docker** - Containerization
- **Render** - Cloud hosting

### Development Tools
- **Swagger/OpenAPI** - API documentation
- **ESLint & Prettier** - Code quality
- **Git** - Version control
- **Taiga** - Project management

## 👥 Development Team

| Role | Developer | GitHub |
|------|-----------|--------|
| **Project Lead & Full Stack** | Víctor Díez | [@inkih04](https://github.com/inkih04) |
| **Full Stack Developer** | David Mas | [@PatoPro121](https://github.com/PatoPro121) |
| **Backend Developer** | Pol Sancho | [@PolSB968](https://github.com/PolSB968) |
| **Frontend Developer** | David Sanz | [@DavidSanzMartinez](https://github.com/DavidSanzMartinez) |

## 📸 Application Screenshots

### Frontend Interface (Next.js)
<details>
<summary>🖱️ Click to view screenshots</summary>

![Main Dashboard](https://github.com/inkih04/SabanaFront/blob/main/images/issues.png)
*Modern React-based dashboard with issue overview*

![Advanced Filters](https://github.com/inkih04/SabanaFront/blob/main/images/filter.png)
*Comprehensive filtering and sorting options*

![Create Issue](https://github.com/inkih04/SabanaFront/blob/main/images/create.png)
*Intuitive issue creation interface*

![Issue Details](https://github.com/inkih04/SabanaFront/blob/main/images/issue.png)
*Detailed issue view with full information*
</details>

### Backend Web Interface (Django)
<details>
<summary>🖱️ Click to view screenshots</summary>

![Web Dashboard](https://github.com/inkih04/SabanaBack/blob/main/images/Issues.png)
*Traditional web interface with Google OAuth*

![API Documentation](https://github.com/inkih04/SabanaBack/blob/main/images/API.png)
*Interactive Swagger API documentation*
</details>

## 🚀 Getting Started

### Quick Start with Live Demos
1. **Frontend**: Visit [saba-front-end.vercel.app](https://saba-front-end.vercel.app/)
2. **Backend Web**: Visit [it22d-backend.onrender.com](https://it22d-backend.onrender.com/)
3. **API Docs**: Explore [API Documentation](https://it22d-backend.onrender.com/swagger/)

### Local Development Setup

#### Frontend Setup
```bash
# Clone frontend repository
git clone https://github.com/inkih04/SabanaFront.git
cd SabanaFront

# Install dependencies
npm install

# Run development server
npm run dev
# Access at http://localhost:3000
```

#### Backend Setup
```bash
# Clone backend repository
git clone https://github.com/inkih04/SabanaBack.git
cd SabanaBack

# Run with Docker
docker-compose up --build
# Access at http://localhost:8000
```

## 📊 Project Metrics & Achievements

### 🏆 Academic Results
- **Frontend Grade**: 8.5/10 - Excellent modern frontend implementation
- **Backend Grade**: 9.5/10 - Outstanding full-stack architecture
- **Course**: ASW (Aplicaciones y Servicios Web)

### 📈 Technical Achievements
- ✅ **Full-stack architecture** with clear separation of concerns
- ✅ **Multiple deployment strategies** (Vercel + Render)
- ✅ **Comprehensive API documentation** with Swagger/OpenAPI
- ✅ **Responsive design** optimized for all devices
- ✅ **Modern development practices** with ESLint, Prettier, Docker
- ✅ **Authentication systems** for different use cases
- ✅ **Performance optimization** with SSR/SSG and caching
- ✅ **Professional deployment** with CI/CD best practices

## ⚠️ Current Limitations & Notes

### 🔐 Authentication Variations
- **Frontend**: Uses pre-defined users (academic requirement)
- **Backend**: Full Google OAuth integration for web interface

### 📎 File Upload Status
- **Architecture**: Complete file upload system implemented
- **Current Status**: Temporarily disabled due to AWS Student account expiration
- **AWS S3 Integration**: Ready for reactivation when credentials are renewed

### 🌐 Hosting Considerations
- **Render Free Tier**: Backend may experience cold starts (30-60 seconds)
- **Vercel**: Frontend has optimal performance with edge deployment

## 📌 Project Management

We utilized **Agile/Scrum methodology** throughout development:

🔗 **[Taiga Board](https://tree.taiga.io/project/victordiez-it22dasw/taskboard/sprint-1-22919)** - Complete sprint planning and task tracking

### Development Methodology
- **Sprint Planning**: 2-week sprints with clear deliverables
- **Daily Standups**: Regular team synchronization
- **Code Reviews**: Peer review process for quality assurance
- **GitFlow**: Structured branching strategy for organized development

## 🎓 Academic Context

This project was developed for the **ASW (Aplicaciones y Servicios Web)** course, demonstrating:

- **Full-stack development** with modern frameworks
- **API design and documentation** following REST principles
- **Multiple deployment strategies** and cloud hosting
- **Team collaboration** and agile project management
- **Authentication systems** and security best practices
- **Performance optimization** and scalability considerations
- **Professional documentation** and code organization

## 🔗 Repository Structure

```
Sabana Project
├── Frontend Repository (SabanaFront)
│   ├── Next.js application
│   ├── React components
│   ├── API integration layer
│   └── Vercel deployment
└── Backend Repository (SabanaBack)
    ├── Django web application
    ├── REST API with DRF
    ├── Authentication systems
    ├── Database models
    └── Docker deployment
```

## 📝 License

This project was developed for educational purposes as part of university coursework.

---

<div align="center">

**🌾 Developed with ❤️ by the Sabana Team**

[![Frontend](https://img.shields.io/badge/Frontend-Next.js-black?style=for-the-badge&logo=next.js)](https://github.com/inkih04/SabanaFront)
[![Backend](https://img.shields.io/badge/Backend-Django-green?style=for-the-badge&logo=django)](https://github.com/inkih04/SabanaBack)
[![API](https://img.shields.io/badge/API-REST-blue?style=for-the-badge&logo=swagger)](https://it22d-backend.onrender.com/swagger/)

</div>
