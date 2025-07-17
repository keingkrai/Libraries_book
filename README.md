
# 📚 Libraries Book Management System

โปรเจกต์นี้เป็นระบบจัดการหนังสือในห้องสมุด โดยใช้ **React (Frontend)** และ **Node.js (Backend)**  
รองรับการจัดเก็บข้อมูลหนังสือ, ยืม-คืนหนังสือ และแสดงสถานะการใช้งานแบบเรียลไทม์  

---

## ✅ คุณสมบัติเด่น (Features)
- ✅ จัดการรายการหนังสือ (เพิ่ม, ลบ, แก้ไข)  
- ✅ ระบบยืม-คืนหนังสือ พร้อมบันทึกประวัติ  
- ✅ ค้นหาหนังสือแบบรวดเร็ว  
- ✅ แสดงสถานะหนังสือ (ว่าง / ยืมอยู่)  
- ✅ Dashboard แสดงสถิติการใช้งาน  

---

## 🏗 สถาปัตยกรรมระบบ (Architecture)
```
React (Frontend)  <—API—>  Node.js (Backend)  <—>  Database (MongoDB)
```

---

## 🖥 เทคโนโลยีที่ใช้ (Tech Stack)
- **Frontend:** React, Tailwind CSS  
- **Backend:** Node.js, Express  
- **Database:** MongoDB  
- **อื่น ๆ:** Axios, JWT Authentication  

---

## 🚀 วิธีใช้งาน (Installation)
```bash
# Clone Project
git clone https://github.com/keingkrai/Libraries_book.git

# เข้าโฟลเดอร์
cd Libraries_book

# ติดตั้ง dependencies (Backend)
cd server
npm install

# ติดตั้ง dependencies (Frontend)
cd ../client
npm install

# รัน Backend
cd ../server
npm start

# รัน Frontend
cd ../client
npm start
```

---

## 🗂 โครงสร้างโปรเจกต์ (Project Structure)
```
Libraries_book/
├── client/        # React Frontend
│   ├── src/
│   └── ...
├── server/        # Node.js Backend
│   ├── routes/
│   ├── models/
│   └── ...
└── README.md
```

---

## ✅ ฟีเจอร์ในอนาคต (Future Features)
- ✅ รองรับระบบจองหนังสือออนไลน์  
- ✅ การแจ้งเตือนวันครบกำหนดยืม  
- ✅ เชื่อมต่อ API ภายนอกสำหรับหนังสืออิเล็กทรอนิกส์  

---

## 📌 License
MIT License

---

## 👤 ผู้พัฒนา
**Keingkrai Buakeaw**  
GitHub: [@keingkrai](https://github.com/keingkrai)  
