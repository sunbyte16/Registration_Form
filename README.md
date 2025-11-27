<div align="center">

# � Registration Form

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sunbyte16/Registration_Form)
[![Made with Love](https://img.shields.io/badge/Made%20With-Love-orange.svg)](https://github.com/sunbyte16)
[![GitHub Stars](https://img.shields.io/github/stars/sunbyte16/Registration_Form?style=social)](https://github.com/sunbyte16/Registration_Form/stargazers)

<br/>

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="mongodb" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" alt="express" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="react" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="nodejs" width="50" height="50"/>

<br/>

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)

<br/>

<p align="center">
  <b>A modern, responsive registration form built with the MERN stack</b>
</p>

<p align="center">
  <a href="https://your-demo-link.com">
    <img src="https://img.shields.io/badge/LIVE-DEMO-brightgreen?style=for-the-badge" alt="Live Demo" />
  </a>
  <a href="https://github.com/sunbyte16/Registration_Form/issues">
    <img src="https://img.shields.io/badge/REPORT-BUG-red?style=for-the-badge" alt="Report Bug" />
  </a>
  <a href="https://github.com/sunbyte16/Registration_Form/issues">
    <img src="https://img.shields.io/badge/REQUEST-FEATURE-blue?style=for-the-badge" alt="Request Feature" />
  </a>
</p>

</div>

## ✨ Features

- 🎯 User-friendly registration interface
- 💾 MongoDB database integration
- ✅ Real-time form validation
- 📱 Responsive design
- 🔐 Secure data handling
- ⚡ Fast and efficient

## 🛠️ Prerequisites

<details>
<summary>Required Software & Tools</summary>

| Tool | Version | Description |
|------|---------|-------------|
| [![Node.js](https://img.shields.io/badge/Node.js-v14+-green?style=flat-square&logo=node.js)](https://nodejs.org/) | v14+ | JavaScript Runtime |
| [![MongoDB](https://img.shields.io/badge/MongoDB-Latest-green?style=flat-square&logo=mongodb)](https://www.mongodb.com/) | Latest | Database |
| [![NPM](https://img.shields.io/badge/NPM-Latest-red?style=flat-square&logo=npm)](https://www.npmjs.com/) | Latest | Package Manager |

</details>

## Installation

1. Clone the repository:
```bash
git clone https://github.com/sunbyte16/Registration_Form.git
cd Registration_Form
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your MongoDB connection string:
```
MONGODB_URI=mongodb://localhost:27017/registration_form
```

## Running the Application

1. Start the backend server:
```bash
npm run server
```

2. In a new terminal, start the React frontend:
```bash
npm start
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000

## Project Structure

```
Registration_Form/
├── package.json
├── server.js
├── .env
├── public/
│   └── index.html
├── src/
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   ├── config/
│   │   └── db.js
│   ├── models/
│   │   └── User.js
│   └── components/
│       └── RegistrationForm/
│           ├── index.js
│           └── index.css
```

## 🔌 API Endpoints

| Method | Endpoint | Description | Request Body |
|--------|----------|-------------|--------------|
| ![POST](https://img.shields.io/badge/POST-green?style=for-the-badge) | `/api/register` | Register a new user | ```Sunil
{
  "name": "string",
  "email": "string"
}


## 🔧 Technologies Used

<details>
<summary>Frontend Technologies</summary>

| Technology | Description |
|------------|-------------|
| ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) | UI Library |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) | Styling |
| ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white) | HTTP Client |

</details>

<details>
<summary>Backend Technologies</summary>

| Technology | Description |
|------------|-------------|
| ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white) | Runtime Environment |
| ![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white) | Backend Framework |
| ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) | Database |
| ![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white) | ODM |

</details>

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 👤 Connect With Me

[![Portfolio](https://img.shields.io/badge/Portfolio-255E63?style=for-the-badge&logo=About.me&logoColor=white)](https://lively-dodol-cc397c.netlify.app)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sunbyte16)
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sunil-kumar-bb88bb31a/)

---
![Created By](https://img.shields.io/badge/Created%20By-Sunil%20Sharma-blue?style=for-the-badge)

Made with ❤️ and ☕

![Built With Love](https://forthebadge.com/images/badges/built-with-love.svg)




- [GitHub Pages](https://pages.github.com)

- [Font Awesome](https://fontawesome.com)

