## 📌 Overview

The ICSCIS website provides:

- Conference information
- Advisory and organizing committees
- Technical tracks and sessions
- Registration details
- Announcements and updates

The project is designed as a fast, maintainable, and easily deployable static website.

---

## 🛠 Tech Stack

- **HTML5** – Website structure and content
- **Tailwind CSS** – Utility-first styling framework
- **PostCSS** – CSS processing
- **Autoprefixer** – Automatic vendor prefix handling
- **Node.js + npm** – Build tools and dependency management

---

## 📂 Project Structure
```

ICSCIS-Website/
│
├── index.html # Main landing page
├── *.html # Other website pages
├── components/ # Reusable HTML components
├── src/
│ └── input.css # Tailwind source file
├── assets/
│ └── css/
│ └── output.css # Generated Tailwind CSS 
├── package.json # Project configuration and scripts
└── README.md # Project documentation

```
---

## ⚙️ Prerequisites

Before running the project, ensure you have:

- **Node.js (v18 or higher recommended)**
- **npm**

Check installed versions:


node -v
npm -v


---

## 🚀 Getting Started

### 1️⃣ Clone the Repository


git clone https://github.com/BhavyaAgrawa12/icscis-website.git

cd icscis-website


### 2️⃣ Install Dependencies


npm install


### 3️⃣ Run Development Mode

Watches `src/input.css` and rebuilds `assets/css/output.css` automatically:


npm run dev


### 4️⃣ Build for Production

Generates a minified CSS file for deployment:


npm run build


---

## 📜 Available Scripts

| Command | Description |
|----------|-------------|
| `npm run dev` | Watches Tailwind source file and rebuilds CSS |
| `npm run build` | Creates minified production CSS |

---

## 🌍 Deployment

Since this is a static website, it can be deployed on:

- GitHub Pages  
- Netlify  
- Vercel (static hosting)  
- Any Apache/Nginx server  
- Institutional hosting platforms  

### GitHub Pages Deployment

1. Push the repository to GitHub.
2. Navigate to **Settings → Pages**.
3. Select the main branch as the source.
4. Save and publish.

---

## ✨ Development Guidelines

- Do **not edit** `assets/css/output.css` directly.
- Modify styles only in `src/input.css`.
- Keep reusable sections inside the `components/` directory.
- Maintain clean, semantic HTML structure.
- Ensure consistent formatting and naming conventions.

---

## 🤝 Contributing

Contributions are welcome:

1. Fork the repository  
2. Create a new feature branch  
3. Commit your changes  
4. Submit a Pull Request  

---

## 📄 License

This project is intended for academic and conference use.

---

## 📬 Contact

For website-related queries, please contact the ICSCIS Organizing Committee.