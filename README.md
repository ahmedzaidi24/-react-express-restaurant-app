# Restaurant Ordering Web App – React + Express.js

## 🧠 Overview  
This full-stack restaurant ordering system was developed for the unit **COMP6006: Web Application Frameworks** at Curtin University. It simulates a food ordering experience from the user’s perspective using a **React-based frontend** and an **Express.js-powered backend API**. The goal was to explore the distinctions between client-rendered and server-rendered systems, while also building scalable UI and backend logic in a modular fashion.

---

## 🎯 Objective  
To build a responsive food ordering platform that allows users to:
- View a menu with item names, images, and prices
- Add items to cart and place an order
- View previous orders and delete them
- Interact with backend APIs for all operations
- Reflect order data using persistent JSON structure

---

## 🧩 Backend (Express.js)
- API server built in `app.js`
- Menu stored in `data.json`
- Orders handled via REST routes
- Lightweight database via JSON storage

### API Endpoints:
| Method | Endpoint           | Purpose                 |
|--------|--------------------|-------------------------|
| GET    | `/menu`            | Fetch available items   |
| POST   | `/order`           | Place a new order       |
| GET    | `/past-orders`     | Fetch past orders       |
| DELETE | `/past-orders/:id` | Delete specific order   |

---

## ⚛️ Frontend (React.js)
- Built with **React Functional Components**
- State managed via **useState** and **useEffect**
- Clean UI using **Bootstrap CSS**
- Structured into components: `MenuList`, `Cart`, `OrderHistory`

> 🔁 The frontend connects to backend endpoints on `localhost:3000`

---

## 📈 Key Results  
- ✅ Fully functional UI with real-time cart updates  
- ✅ API-based order placement and history retrieval  
- ✅ All functionality simulated using only frontend + JSON  
- ✅ Frontend and backend run independently (decoupled system)  
- 🔄 Demonstrated separation of concerns between UI and logic

---

## 🧠 Reflections  
This project gave me hands-on experience with **React component design**, **stateful logic**, and **backend API integration**. Compared to server-rendered systems like Django, this approach offers more flexibility and responsiveness, especially for consumer-facing platforms.

Working with `Express.js` also deepened my understanding of request handling, middleware, and modular backend setups, which is critical for scalable full-stack development.

---

## 🛠️ Tools & Technologies  
- `React.js`  
- `Express.js`  
- `Node.js`  
- `Bootstrap`  
- `JSON`  
- `VSCode`, `npm`

---

## 📁 Files Included  
| File / Folder         | Description                         |
|-----------------------|-------------------------------------|
| `app.js`              | Main Express server code            |
| `data.json`           | Menu and order storage (JSON)       |
| `package.json`        | Backend dependencies                |
| `package-lock.json`   | Package lock for consistent install |
| `20972008_Answers.docx` | Explanation of system logic       |
| `Requirements.pdf`    | Assignment brief & expectations     |

---

## 👤 Author  
**Syed Muhammad Ahmed Zaidi**  
Curtin University – COMP6006  

---

## 📄 License  
For academic and demonstration purposes only. Contact author for further use.

