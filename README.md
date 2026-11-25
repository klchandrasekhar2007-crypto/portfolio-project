# 🧑‍💻 K.L.Chandra Sekhar Personal Portfolio Website

A complete, responsive personal portfolio website built with **React + Vite**, featuring a public portfolio and a fully functional admin dashboard.

## ✨ Features

### User Module (Public Portfolio)
- **Home** – Hero section with intro, stats, and CTA buttons
- **About** – Personal bio, education timeline, quick-info highlights
- **Skills** – Visual skill progress bars, filterable by category
- **Projects** – Project cards with tech tags, GitHub & live demo links
- **Achievements** – Certifications and awards display
- **Blog** – Blog posts with Read More modal
- **Contact** – Validated contact form (saves to LocalStorage)

### Admin Module (Dashboard)
- Secure Login & Signup (LocalStorage-based)
- Dashboard overview with live statistics
- **Project Management** – Add, Edit, Delete projects (reflects on public site instantly)
- **Skills Management** – Add, Delete skills with visual progress bar
- **Blog Management** – Write and delete blog posts
- **Messages** – View and delete contact form submissions

## 🛠 Tech Stack

| Technology       | Purpose                          |
|-----------------|----------------------------------|
| React 18        | UI framework                     |
| Vite            | Build tool and dev server        |
| React Router v6 | Client-side routing              |
| Lucide React    | Icon library                     |
| LocalStorage    | Data persistence & authentication|
| CSS3            | Custom styling (no frameworks)   |

## 📁 Project Structure

```
src/
├── components/
│   ├── Navbar.jsx
│   ├── Footer.jsx
│   ├── ProjectCard.jsx
│   ├── ProtectedRoute.jsx
│   └── AdminLayout.jsx
├── context/
│   └── AuthContext.jsx
├── pages/
│   ├── Home.jsx
│   ├── About.jsx
│   ├── Skills.jsx
│   ├── Projects.jsx
│   ├── Achievements.jsx
│   ├── Blog.jsx
│   ├── Contact.jsx
│   └── admin/
│       ├── Login.jsx
│       ├── Signup.jsx
│       ├── Dashboard.jsx
│       ├── ManageProjects.jsx
│       ├── ManageSkills.jsx
│       ├── ManageBlogs.jsx
│       └── Messages.jsx
└── utils/
    └── storage.js
```

## 🚀 Getting Started

### Prerequisites
- Node.js ≥ 18
- npm ≥ 9

### Installation

```bash
# Clone the repo
git clone https://github.com/your-username/portfolio.git
cd portfolio

# Install dependencies
npm install

# Start development server
npm run dev
```

The app will be available at **http://localhost:5173**

## 🔐 Admin Access

### Demo Credentials
| Field    | Value                  |
|----------|------------------------|
| Email    | admin@portfolio.com    |
| Password | admin123               |

Go to `http://localhost:5173/admin/login` to sign in.

## 📦 Build for Production

```bash
npm run build
```

Output is in the `dist/` folder.

## 🌐 Deploy to Vercel

### Method 1 – Vercel CLI
```bash
npm install -g vercel
vercel login
vercel --prod
```

### Method 2 – GitHub Integration
1. Push to GitHub
2. Go to [vercel.com](https://vercel.com) → **New Project**
3. Import your repository
4. Framework: **Vite**
5. Click **Deploy**

> The `vercel.json` file is already included for SPA routing support.

## 📝 License

MIT – Free to use for academic and personal projects.

"# portfolio-project" 
"# personal-portfolio-website-chandu" 
