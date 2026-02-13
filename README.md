# Priya Kumari - Portfolio Website

<div align="center">
  <h2>🚀 Full-Stack Developer & UI/UX Enthusiast</h2>
  <p>A modern, responsive portfolio website built with React and Tailwind CSS</p>
  
  ![Portfolio Demo](https://img.shields.io/badge/React-18.3.1-blue?style=for-the-badge&logo=react)
  ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.1-38B2AC?style=for-the-badge&logo=tailwind-css)
  ![Vite](https://img.shields.io/badge/Vite-7.1.3-646CFF?style=for-the-badge&logo=vite)
</div>

---

## 📋 About This Portfolio

Welcome to my personal portfolio website! This site showcases my journey as a **Full-Stack Developer**, featuring my skills, projects, education, and professional experience. Built with modern web technologies, it provides an interactive and engaging way to explore my work and get in touch with me.

---

## 🌟 Features

- **🎨 Modern Design**: Clean, professional UI with smooth animations
- **📱 Fully Responsive**: Optimized for all devices and screen sizes
- **⚡ Fast Performance**: Built with Vite for lightning-fast loading
- **🎭 Interactive Elements**: Engaging animations and hover effects
- **📧 Contact Form**: Functional contact form with Formspree integration
- **🌙 Smooth Navigation**: Seamless routing between sections
- **💫 Visual Effects**: Meteors, sparkles, and gradient animations

---

## 🏗️ Project Structure

```
portfolio/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   ├── css/
│   │   │   ├── index.css
│   │   │   ├── Header.css
│   │   │   └── tomorrow.css
│   │   └── images/
│   │       ├── favicon.ico
│   │       ├── hero.jpg
│   │       ├── wanderlust.png
│   │       ├── VocalDesk.png
│   │       └── ResumeBuilder.png
│   ├── components/
│   │   ├── ui/
│   │   │   ├── badge.jsx
│   │   │   ├── button.jsx
│   │   │   ├── card.jsx
│   │   │   ├── cool-mode.jsx
│   │   │   ├── EducationLoader.jsx
│   │   │   ├── evervault-card.jsx
│   │   │   ├── flip-words.jsx
│   │   │   ├── icon-cloud.jsx
│   │   │   ├── meteors.jsx
│   │   │   ├── sparkles-text.jsx
│   │   │   └── tooltip.jsx
│   │   ├── AnimatedGrid.jsx
│   │   ├── enhanced-portfolio-card.jsx
│   │   └── globe.jsx
│   ├── lib/
│   │   └── utils.js
│   ├── pages/
│   │   ├── About/
│   │   │   └── About.jsx
│   │   ├── Contact/
│   │   │   └── Contact.jsx
│   │   ├── Education/
│   │   │   └── Education.jsx
│   │   ├── Experience/
│   │   │   └── Experience.jsx
│   │   ├── Header/
│   │   │   └── Header.jsx
│   │   ├── Hero/
│   │   │   └── Hero.jsx
│   │   ├── Projects/
│   │   │   └── Projects.jsx
│   │   └── Skills/
│   │       └── Skills.jsx
│   ├── App.jsx
│   └── main.jsx
├── Configuration Files
│   ├── .gitignore
│   ├── components.json
│   ├── eslint.config.js
│   ├── index.html
│   ├── jsconfig.json
│   ├── package.json
│   ├── postcss.config.js
│   ├── tailwind.config.js
│   ├── vercel.json
│   └── vite.config.js
```

---

## 🎯 Portfolio Sections

### 🏠 **Hero Section**
- Interactive introduction with animated text
- Code snippet showcasing my profile
- Call-to-action buttons linking to GitHub and resume

### 💼 **About Me**
- Personal introduction and background
- Professional journey and interests
- Skills overview with visual elements

### 🛠️ **Skills**
- **Frontend**: React, TypeScript, Tailwind CSS, HTML5, CSS3
- **Backend**: Node.js, Python, Express, EJS
- **Database**: MySQL, MongoDB
- **Tools**: Git, Docker, VS Code, Figma
- **Cloud**: AWS, Vercel, Firebase

### 🎓 **Education**
- Bachelor of Computer Science Engineering (2023-Present)
- Higher Secondary Certificate - Science (2021-2023)
- Academic achievements and relevant coursework

### 💻 **Projects**
Featured projects with live demos and source code:
- **Wanderlust**: Travel booking platform
- **VocalDesk**: Voice-controlled desktop assistant
- **Resume Builder**: Full-stack resume creation tool

### 📞 **Contact**
- Functional contact form with Formspree integration
- Direct email: kumaripriyee73@gmail.com
- Social media links and professional profiles

---

## 🚀 Technologies Used

### **Frontend**
- **React 18.3.1** - Modern JavaScript library
- **Vite 7.1.3** - Fast build tool and dev server
- **Tailwind CSS 3.4.1** - Utility-first CSS framework
- **Framer Motion** - Animation library
- **React Router DOM** - Client-side routing

### **UI Components**
- **Lucide React** - Beautiful icons
- **React Icons** - Popular icon library
- **Custom UI Components** - Reusable component library

### **Development Tools**
- **ESLint** - Code linting
- **PostCSS** - CSS processing
- **Autoprefixer** - CSS vendor prefixes

### **Deployment**
- **Vercel** - Hosting and deployment platform

---

## ⚡ Quick Start

### Prerequisites
- **Node.js** (v18 or higher)
- **npm** or **yarn**
- **Git**

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Priyakumari0307/portfolio.git
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
npm run preview
```

---

## 📧 Contact Form Setup

The contact form uses **Formspree** for handling form submissions:

1. The form is configured to send emails to: `kumaripriyee73@gmail.com`
2. Formspree endpoint: `https://formspree.io/f/xgozggej`
3. All form submissions are automatically forwarded to the specified email

---

## 🎨 Customization

### Colors and Themes
- Primary colors defined in `tailwind.config.js`
- CSS custom properties in `src/assets/css/index.css`
- Dark theme with blue/teal accent colors

### Adding New Sections
1. Create a new component in `src/pages/`
2. Add routing in `src/App.jsx`
3. Update navigation in `src/pages/Header/Header.jsx`

---

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:
- **Desktop** (1920px and above)
- **Laptop** (1366px - 1919px)
- **Tablet** (768px - 1365px)
- **Mobile** (320px - 767px)

---

## 🚀 Deployment

This portfolio is deployed on **Vercel** with automatic deployments from the main branch.

### Deploy Your Own
1. Fork this repository
2. Connect your GitHub account to Vercel
3. Import the project and deploy
4. Update the contact form endpoint with your own Formspree URL

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📞 Get In Touch

- **Email**: kumaripriyee73@gmail.com
- **GitHub**: [@Priyakumari0307](https://github.com/Priyakumari0307)
- **Portfolio**: [Live Demo](https://portfolio-97h6.vercel.app/)

---

<div align="center">
  <p>Made with ❤️ by <strong>Priya Kumari</strong></p>
  <p>⭐ Star this repo if you found it helpful!</p>
</div>
