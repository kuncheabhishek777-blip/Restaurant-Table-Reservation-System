<div align="center">

# 🍽️ Restaurant Table Reservation System 🪑

### *Book. Dine. Enjoy.*

A full-stack web application that lets customers reserve restaurant tables online in real time — while giving restaurant admins a powerful dashboard to manage tables, bookings, and occupancy.

![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-ff4b4b?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![GLA University](https://img.shields.io/badge/GLA%20University-Project-1F4E78?style=for-the-badge)

<br/>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />

</div>

---

## 🍷 About the Project

Ever tried calling a restaurant during peak hours and gotten stuck on hold — or worse, shown up to find your "reserved" table was double-booked? **Restaurant Table Reservation System** fixes that.

This full-stack platform lets customers check **real-time table availability**, book instantly, and manage their reservations — while restaurant staff get a centralized dashboard to configure tables, track bookings, and cut down on no-shows and scheduling chaos.

> Built as a full-stack academic project at **GLA University**, Department of Computer Science & Engineering (AI & ML).

---

## 🌟 Key Features

| Feature | Description |
|---|---|
| 🔍 **Real-Time Availability** | Search tables by date, time slot, and party size |
| 📅 **Instant Booking** | Reserve a table in seconds with automatic conflict checks |
| 🚫 **No Double-Booking** | Server-side validation prevents overlapping reservations |
| 👤 **Customer Dashboard** | View, modify, or cancel your own reservations anytime |
| 🛠️ **Admin Panel** | Add/edit tables, manage capacity, and control operating hours |
| 📊 **Reservation Insights** | Track daily bookings, peak hours, and table occupancy |
| ✅ **Status Management** | Mark bookings as Pending, Confirmed, Completed, or No-show |
| 📧 **Email Confirmations** | Automatic booking & cancellation notifications |
| 🔐 **Secure Authentication** | JWT-based login with encrypted passwords |
| 📱 **Fully Responsive** | Works seamlessly on desktop, tablet, and mobile |

---

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology |
|---|---|
| 🎨 Frontend | React.js, HTML5, CSS3, JavaScript, Bootstrap / Tailwind CSS |
| ⚙️ Backend | Node.js, Express.js (REST API) |
| 🗄️ Database | MongoDB (or MySQL / PostgreSQL) |
| 🔑 Authentication | JWT, bcrypt |
| ☁️ Deployment | Vercel / Netlify (frontend), Render / Railway (backend), MongoDB Atlas |
| 🧪 Testing | Postman, Jest / React Testing Library |
| 🎯 Version Control | Git & GitHub |

</div>

---

## 🏗️ System Architecture

```
Customer / Admin (Browser)
        │
        ▼
   React Frontend (SPA)
        │  HTTPS / JSON
        ▼
  Node.js + Express REST API
        │
        ▼
     MongoDB Database
 (Users | Tables | Reservations)
```

---

## 📸 Screenshots

<div align="center">

| Home / Search | Booking Flow | Admin Dashboard |
|---|---|---|
| *coming soon* | *coming soon* | *coming soon* |

</div>

> 💡 Swap these placeholders with real screenshots or GIFs once the UI is ready.

---

## 🚀 Getting Started

### Prerequisites
Make sure you have installed:
- [Node.js](https://nodejs.org/) (v16 or above)
- [MongoDB](https://www.mongodb.com/) (local or Atlas)
- [Git](https://git-scm.com/)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/restaurant-table-reservation-system.git

# 2. Navigate into the project directory
cd restaurant-table-reservation-system

# 3. Install backend dependencies
cd server
npm install

# 4. Install frontend dependencies
cd ../client
npm install
```

### Environment Variables

Create a `.env` file inside the `server` folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email_for_notifications
EMAIL_PASS=your_email_app_password
```

### Run the App

```bash
# Start backend (from /server)
npm run dev

# Start frontend (from /client)
npm start
```

The app will be live at `http://localhost:3000` 🍽️

---

## 📂 Folder Structure

```
restaurant-table-reservation-system/
├── client/                  # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── App.js
│   └── package.json
├── server/                   # Node/Express backend
│   ├── models/
│   │   ├── User.js
│   │   ├── Table.js
│   │   └── Reservation.js
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── config/
│   └── server.js
├── .gitignore
├── README.md
└── LICENSE
```

---

## 🗄️ Core Data Model

| Entity | Key Fields |
|---|---|
| **User** | name, email, password (hashed), role |
| **Table** | table number, capacity, location, status |
| **Reservation** | user_id, table_id, date, time_slot, party_size, status |

---

## 🗺️ Roadmap

- [x] User authentication (customer & admin)
- [x] Real-time table availability search
- [x] Reservation creation with conflict prevention
- [x] Admin dashboard for table & booking management
- [ ] Online payment / deposit integration
- [ ] SMS/WhatsApp reminders
- [ ] Multi-branch restaurant support
- [ ] AI-based smart slot recommendations

---

## 🤝 Contributing

Contributions make the open-source community amazing! Any contributions are **greatly appreciated**.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 👤 Author

<div align="center">

**Kunche Abhishek**

B.Tech CSE (AI & ML) | GLA University | Roll No. 22515500050

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kuncheabhishek777-blip)

</div>

---

<div align="center">

### 🍽️ *"Great meals start with a great reservation."*

⭐ **If you like this project, don't forget to star the repo!** ⭐

</div>
