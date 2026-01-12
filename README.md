# DeNote

DeNote is a **full-stack notes sharing application** that allows users to upload, discover, and access academic notes securely using a **Node.js + Express backend**, **MongoDB**, and **IPFS via Pinata**.

---

## 🚀 Features
- User authentication using **JWT**
- Upload and store notes via **IPFS (Pinata)**
- Metadata stored in **MongoDB**
- Secure backend with environment-based configuration
- **Decentralized Storage** - Notes are permanently pinned to IPFS through Pinata
- **Smart Discovery System** - Find notes based on community ratings and popularity
- **Rating System** - Users can rate notes to identify quality material
- **PDF Preview** - View notes directly using IPFS gateway links

---

## � Tech Stack
- **Backend:** Node.js, Express
- **Frontend:** React, Vite
- **Database:** MongoDB Atlas
- **Storage:** IPFS (Pinata)
- **Auth:** JSON Web Tokens (JWT)

---

## ⚙️ Environment Variables
Create `config.env` in the root directory:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secure_jwt_secret
PINATA=your_pinata_jwt_token
```

---

## ▶️ Run Locally

### Backend
```bash
npm install
npm start
```
Server runs on `http://localhost:5000`

### Frontend
```bash
cd frontend
npm install
npm run dev
```
Frontend runs on `http://localhost:5173`

---

## 🚀 Deployment
- **Backend:** Render / Railway / EC2
- **Frontend:** Vercel / Netlify
- Set environment variables in the deployment platform

---

## � Security Note
Secrets and credentials are managed using environment variables and are **not committed** to the repository. The `config.env` file is included in `.gitignore`.

---

## 📄 License
Open-source project for learning and educational purposes.
