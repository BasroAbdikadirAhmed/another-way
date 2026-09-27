# ✨ Neura AI — Modern AI SaaS Landing Page

A modern, responsive, and interactive **AI SaaS landing page** built with **HTML, Tailwind CSS, and JavaScript**.

Neura AI is designed to look like a professional startup product website, with a clean dark interface, modern gradients, glassmorphism effects, responsive layouts, pricing cards, FAQ sections, AI chat demo, and interactive UI components.

---

## 🚀 Live Preview

**Project:** Neura AI

**Type:** AI SaaS Landing Page

**Status:** Frontend Demo

---

## 🖥️ Preview

Neura AI includes:

* Modern SaaS hero section
* Responsive navigation
* AI workspace dashboard preview
* AI chat interface
* Feature sections
* Pricing plans
* FAQ accordion
* Customer statistics
* Call-to-action sections
* Footer
* Signup modal
* Login modal
* Contact sales modal
* Dark/light theme button
* Mobile navigation
* Smooth scrolling
* Interactive JavaScript components

---

# ✨ Features

## 🎯 Hero Section

The landing page starts with a modern hero section containing:

* AI SaaS headline
* Gradient typography
* Product description
* Call-to-action buttons
* Customer trust indicators
* Animated dashboard preview

Example:

```text
Your ideas.

Supercharged.
```

---

## 🧠 AI Copilot

Neura AI includes an interactive AI assistant interface.

Users can enter a message such as:

```text
Help me create a marketing plan
```

The frontend displays a simulated AI response.

> Note: The current AI chat is a frontend demo and is not connected to a real AI API.

---

## ⚡ Smart Automation

The website presents automation as one of the main Neura AI features.

Users can learn about:

* Workflow automation
* Productivity
* AI-powered tasks
* Tool integrations

---

## 👥 Team Collaboration

The landing page includes a collaboration feature section showing how teams could use the platform to:

* Share projects
* Collaborate
* Manage tasks
* Use shared AI workflows

---

## 🔎 AI Research

The product concept also includes AI-powered research functionality.

The landing page explains how AI can help users:

* Research information
* Summarize content
* Generate insights
* Organize knowledge

---

## 🔐 Enterprise Security

Neura AI includes an enterprise security section describing:

* Secure workspace
* Privacy
* Team protection
* Enterprise-ready architecture

---

# 💰 Pricing

The website contains three pricing plans.

## Starter

```text
$0 / month
```

Includes:

* 100 AI messages/month
* 3 projects
* Basic automation
* Community support

---

## Pro

```text
$19 / month
```

Includes:

* Unlimited AI conversations
* Unlimited projects
* Advanced automation
* Priority support
* Team collaboration

---

## Enterprise

```text
Custom
```

Includes:

* Everything in Pro
* SSO
* Advanced security
* Dedicated support
* Custom integrations

---

# 📱 Responsive Design

The website is responsive and designed for:

* 💻 Desktop
* 💻 Laptop
* 📱 Tablet
* 📱 Mobile

Tailwind CSS responsive classes are used throughout the project.

Examples:

```html
sm:
md:
lg:
xl:
```

---

# 🎨 Design

The design uses a modern dark SaaS aesthetic.

Main design elements include:

* Dark background
* Purple gradients
* Cyan accents
* Glassmorphism
* Rounded cards
* Soft shadows
* Gradient typography
* Animated elements
* Minimal interface

---

# 🛠️ Technologies

This project uses:

### HTML5

Used to build the structure of the website.

```html
<!DOCTYPE html>
<html>
```

---

### Tailwind CSS

Used for:

* Layout
* Responsive design
* Colors
* Spacing
* Typography
* Components
* Animations

Tailwind CSS is loaded through the CDN:

```html
<script src="https://cdn.tailwindcss.com"></script>
```

---

### JavaScript

JavaScript handles the interactive functionality.

Examples:

* Mobile menu
* Modal windows
* FAQ accordion
* AI chat demo
* Theme button
* Signup form
* Login interaction
* Pricing buttons
* Smooth scrolling

---

### Lucide Icons

The project uses Lucide icons.

```html
<script src="https://unpkg.com/lucide@latest"></script>
```

Icons are initialized with:

```javascript
lucide.createIcons();
```

---

# 📂 Project Structure

The project currently uses a simple single-file structure.

```text
neura-ai/
│
├── index.html
│
└── README.md
```

---

# 📄 Main File

## `index.html`

This file contains:

* HTML
* Tailwind CSS configuration
* Custom CSS
* JavaScript
* UI components
* Responsive design
* Interactive functionality

Everything is currently contained inside one file for easy testing and learning.

---

# ⚙️ Installation

No Node.js or npm is required for the current version.

## Step 1

Create a folder:

```text
neura-ai
```

---

## Step 2

Inside the folder create:

```text
index.html
```

---

## Step 3

Paste the complete Neura AI code into:

```text
index.html
```

---

## Step 4

Save the file.

---

## Step 5

Open:

```text
index.html
```

in your browser.

You can simply double-click the file.

---

# 🌐 Internet Requirement

The current version uses external CDN resources.

Tailwind CSS:

```text
cdn.tailwindcss.com
```

Lucide:

```text
unpkg.com/lucide
```

Therefore, an internet connection is recommended when opening the page.

---

# 🧩 JavaScript Functionality

## Mobile Menu

The mobile menu opens when the menu button is clicked.

```javascript
menuBtn.addEventListener("click", () => {
    mobileMenu.classList.toggle("hidden");
});
```

---

## Signup Modal

The signup modal opens when users click:

```text
Start free
```

The modal contains:

* Name
* Email
* Submit button

---

## FAQ Accordion

The FAQ section uses JavaScript to open and close answers.

Example:

```javascript
button.addEventListener("click", () => {
    current.classList.toggle("open");
});
```

---

## AI Chat

The AI chat is currently simulated on the frontend.

Users can enter a message.

Example:

```text
Create a website for my business
```

The application generates a demo response.

---

# 🤖 Connecting a Real AI API

The current AI chat is only a frontend simulation.

In a production application, it could be connected to a backend.

Possible architecture:

```text
React / HTML
      ↓
Spring Boot REST API
      ↓
AI API
      ↓
Response
      ↓
Frontend
```

For example:

```text
Frontend
   ↓
POST /api/ai/chat
   ↓
Spring Boot
   ↓
AI Service
   ↓
Response
```

---

# 🗄️ Future Backend

A future version of Neura AI could use:

```text
Frontend
   ↓
React
   ↓
Spring Boot
   ↓
PostgreSQL
```

The backend could manage:

* Users
* Authentication
* Projects
* AI conversations
* Subscriptions
* Teams
* Tasks
* Payments
* Usage limits

---

# 🔐 Authentication

Authentication is not implemented in the current frontend-only version.

A future version could include:

```text
Register
Login
Logout
JWT
Refresh Token
Password Reset
Role Management
```

Example architecture:

```text
React
   ↓
POST /api/auth/login
   ↓
Spring Boot
   ↓
PostgreSQL
   ↓
JWT
   ↓
React
```

---

# 🗃️ Future Database

PostgreSQL could be used for the production application.

Possible tables:

```text
users
projects
teams
tasks
conversations
messages
subscriptions
payments
```

Example:

```text
users
 ├── id
 ├── name
 ├── email
 ├── password
 └── role
```

---

# 🚀 Production Version

The current project is a frontend prototype.

A production version could be structured like:

```text
neura-ai/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── App.jsx
│
├── backend/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── dto/
│   ├── exception/
│   └── entity/
│
├── database/
│
└── README.md
```

---

# 🔄 Recommended Full-Stack Architecture

For a more advanced version:

```text
                 ┌───────────────┐
                 │    User       │
                 └───────┬───────┘
                         │
                         ▼
                 ┌───────────────┐
                 │ React +       │
                 │ Tailwind CSS  │
                 └───────┬───────┘
                         │
                    REST API
                         │
                         ▼
                 ┌───────────────┐
                 │ Spring Boot   │
                 └───────┬───────┘
                         │
            ┌────────────┼────────────┐
            │            │            │
            ▼            ▼            ▼
       PostgreSQL     AI API       JWT Auth
```

---

# 📊 Current Project Status

| Feature             | Status     |
| ------------------- | ---------- |
| Landing Page        | ✅ Complete |
| Responsive Design   | ✅ Complete |
| Tailwind CSS        | ✅ Complete |
| JavaScript          | ✅ Complete |
| Mobile Menu         | ✅ Complete |
| FAQ                 | ✅ Complete |
| Pricing             | ✅ Complete |
| Modal               | ✅ Complete |
| AI Demo             | ✅ Complete |
| Theme Button        | ✅ Complete |
| Real Authentication | ⏳ Future   |
| Real AI API         | ⏳ Future   |
| Backend             | ⏳ Future   |
| PostgreSQL          | ⏳ Future   |
| Payments            | ⏳ Future   |
| User Dashboard      | ⏳ Future   |

---

# 🎯 Learning Goals

This project can be used to practice:

* HTML5
* CSS
* Tailwind CSS
* JavaScript DOM
* Responsive design
* UI/UX
* JavaScript events
* Forms
* Modals
* API integration
* Frontend architecture
* REST APIs
* Spring Boot
* PostgreSQL

---

# 🔮 Future Improvements

Possible improvements include:

* [ ] Convert to React
* [ ] Add Spring Boot backend
* [ ] Add PostgreSQL database
* [ ] Add JWT authentication
* [ ] Connect real AI API
* [ ] Add user dashboard
* [ ] Add project management
* [ ] Add team management
* [ ] Add real-time chat
* [ ] Add subscription system
* [ ] Add payment integration
* [ ] Add email verification
* [ ] Add password reset
* [ ] Add admin dashboard
* [ ] Add analytics
* [ ] Deploy frontend
* [ ] Deploy backend
* [ ] Deploy database

---

# 🚀 Deployment

Because this is a static frontend, it can be deployed using services such as:

* GitHub Pages
* Netlify
* Vercel
* Cloudflare Pages

The production full-stack version would require separate deployment for:

```text
Frontend
Backend
Database
```

---

# 📌 Important Note

This project is a **frontend demonstration**.

The following features are simulated:

* AI responses
* Signup
* Login
* Pricing
* Contact sales

They do not currently connect to a real database or backend.

For a real application, these features should be connected to a secure backend API.

---

# 👨‍💻 Author

**Basra Abdikadir Ahmed**

Computer Science Student
Full Stack Development

Interested in:

```text
Frontend Development
Backend Development
Spring Boot
REST APIs
PostgreSQL
AI Applications
Full-Stack Development
```

---

# ⭐ Project Purpose

The purpose of this project is to create a professional modern SaaS interface while practicing frontend development and preparing the project for future full-stack development.

The long-term architecture can evolve from:

```text
HTML
+
Tailwind CSS
+
JavaScript
```

into:

```text
React
+
Tailwind CSS
+
Spring Boot
+
PostgreSQL
+
REST API
+
JWT
+
AI
```

---

# 📜 License

This project is created for learning and portfolio purposes.

You are free to modify the code for your own learning and development.
