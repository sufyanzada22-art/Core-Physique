# 🏋️ CORE PHYSIQUE - Professional Gym Website

A modern, professional website for Core Physique gym located in **Umer Block, Bahria Town**.

## ✨ Features

- Modern responsive design
- 5 complete pages (Home, About, Classes, Trainers, Contact)
- Working contact form with email notifications
- Node.js/Express backend
- Professional animations and effects
- Mobile-friendly

## 🚀 Quick Start

### 1. Install Dependencies
```bash
npm install
```

### 2. Setup Environment
Copy `.env.example` to `.env` and add your email:
```
PORT=3000
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-app-password
```

**For Gmail:**
- Enable 2-Factor Authentication
- Generate App Password: https://myaccount.google.com/apppasswords
- Use the App Password in .env

### 3. Start Server
```bash
npm start
```

### 4. Open Browser
Visit: `http://localhost:3000`

## 📁 Project Structure

```
CorePhysique/
├── server.js              # Express server
├── package.json           # Dependencies
├── .env.example           # Environment template
├── README.md              # This file
└── public/
    ├── index.html         # Home page
    ├── about.html         # About page
    ├── classes.html       # Classes page
    ├── trainers.html      # Trainers page
    ├── contact.html       # Contact page
    ├── css/
    │   └── style.css      # Main stylesheet
    ├── js/
    │   └── main.js        # JavaScript functions
    └── images/            # Image assets
```

## 🎨 Customization

### Colors
Edit `public/css/style.css`:
```css
:root {
    --primary-color: #ff6b35;    /* Orange */
    --secondary-color: #4ecdc4;  /* Teal */
    --accent-color: #f7b731;     /* Yellow */
}
```

### Content
- Update gym info in all HTML files
- Modify pricing in `index.html`
- Edit classes in `classes.html`
- Update trainers in `trainers.html`

## 📧 Contact Information

- **Location:** Umer Block, Bahria Town
- **Phone:** +92 300 1234567
- **Email:** info@corephysique.com
- **Hours:** 5 AM - 11 PM (Daily)

## 🌐 Deployment

### Heroku
```bash
heroku create core-physique
heroku config:set EMAIL_USER=your-email@gmail.com
heroku config:set EMAIL_PASS=your-app-password
git push heroku master
```

### VPS/DigitalOcean
1. Upload files to server
2. Run `npm install`
3. Set environment variables
4. Use PM2: `pm2 start server.js`
5. Setup Nginx reverse proxy

## 🛠️ Technologies

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** Node.js, Express.js
- **Email:** Nodemailer
- **Fonts:** Google Fonts

## 📄 License

Ready for commercial use. Customize and sell as needed.

---

**Built with ❤️ for Core Physique Gym**  
*Transform Your Body, Transform Your Life* 💪
