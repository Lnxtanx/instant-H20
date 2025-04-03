
# 💧 Instant H2O - Water Delivery Web App

Instant H2O is a lightweight, responsive web application built for college campuses or residential areas to allow quick and easy delivery of fresh, cold water into customers' bottles. 💦

## 🚀 Features

- User Signup/Login via Supabase Auth
- Order filtered, chilled water bottles (0.5L, 1L, 2L, 5L)
- Delivery countdown timer (10 minutes)
- Realtime order status updates using Supabase channels
- QR code generation for UPI payments
- Mobile responsive and cross-browser compatible
- Fully built with HTML, CSS, JS (vanilla) + Supabase + Express.js

## 📁 Project Structure

```
waterdelivery/
├── pages/
│   ├── login.html
│   ├── signup.html
│   ├── payment.html
│   ├── orders.html
│   ├── qrcode.min.js
├── index.html
├── server.js
├── supabase.js
├── .env
├── package.json
```

## ⚙️ Technologies Used

- Frontend: HTML, CSS, Vanilla JavaScript
- Backend: Node.js + Express
- Realtime DB/Auth: Supabase
- Deployment: Render

## 🔐 Environment Variables

Create a `.env` file:

```
PORT=3000
SUPABASE_URL=your_supabase_url
SUPABASE_ANON_KEY=your_anon_key
```

## 🧪 Run Locally

```bash
npm install
npm start
```

Then open your browser at [http://localhost:3000](http://localhost:3000)

## ☁️ Deployment (Render)

1. Push code to GitHub
2. Go to [Render](https://render.com) and create a new Web Service
3. Connect your GitHub repo
4. Set build command: `npm install`
5. Set start command: `npm start`
6. Add environment variables from your `.env` file

## 📜 License

This project is licensed under the MIT License.

---

Created with ❤️ by Vivek.
