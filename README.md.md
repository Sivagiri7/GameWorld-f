
# 🎮 GameWorld - Fullstack Web Application

**GameWorld** is a **Fullstack Website** where users can register, log in, and explore game content.  
It includes an **Admin Panel** for managing users and inquiries.

---

## 🛠️ Tech Stack

### Frontend  
- **React.js**  
- **React Router DOM**  
- **Axios**  
- **Tailwind CSS / Custom CSS**

### Backend  
- **Spring Boot (Java)**  
- **MySQL (Railway)**  
- **REST API**

### Deployment  
- **Frontend**: Netlify  
- **Backend**: Render / Railway

---

## 🌟 Features

### User Side  
- Responsive UI  
- User Registration & Login  
- Form submission with **confirmation message**  
- Protected Routes (Only logged-in users can view the website)

### Admin Side  
- View Registered Users  
- Delete Users  
- View & Manage Inquiries

---

## 🗄️ Database Structure

| Table Name   | Fields                         |
|--------------|-------------------------------|
| **users**    | id, name, email, password, role |
| **inquiries**| id, user_id, message, created_at |

---

## 🚀 How to Run Locally

### Frontend (React)

```bash
cd frontend
npm install
npm start
```

### Backend (Spring Boot)

```bash
cd backend
mvn clean install
mvn spring-boot:run
```

### Database  
- Use **Railway / FreeSQLDatabase**  
- Import the SQL file if available  

---

## 🌐 Deployment Links

- **Frontend (Netlify)**: [Live Website](https://your-netlify-link.netlify.app)  
- **Backend (Render / Railway)**: [API Endpoint](https://your-backend-link.onrender.com)

---

## 🖼️ Screenshots

*(Insert Screenshots Here)*

---

## 💬 Contact

For any questions, contact:  
📧 **deepakgameworld@gmail.com**

---

## 📥 Clone the Repository

```bash
git clone https://github.com/your-username/gameworld-fullstack.git
```
