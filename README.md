# 🎮 QuizzWeb – Ứng Dụng Quiz Thời Gian Thực

**QuizzWeb** là một ứng dụng web quiz thời gian thực, được xây dựng phục vụ môn **Công Nghệ Web**.  
Hệ thống cho phép nhiều người chơi tham gia trả lời câu hỏi trực tuyến với trải nghiệm tương tác cao, cập nhật kết quả ngay lập tức.

🔗 Demo: https://cong-nghe-web20251-quizz-web.vercel.app/
<img width="1918" height="912" alt="image" src="https://github.com/user-attachments/assets/9db9d583-3094-41a4-ac7b-1a09411c4b07" />
<img width="1900" height="907" alt="image" src="https://github.com/user-attachments/assets/cef49f90-01d3-4b95-b7cd-e3f3183fa854" />
<img width="1917" height="907" alt="image" src="https://github.com/user-attachments/assets/b0ea24cd-6f9a-4885-8950-7a80710d2e95" />
<img width="1916" height="912" alt="image" src="https://github.com/user-attachments/assets/9445aff1-dc45-4ccc-a9f5-4b12a2731cce" />
<img width="1917" height="903" alt="image" src="https://github.com/user-attachments/assets/bada42b4-c4e9-485a-8a61-530f2c0596ec" />


<img width="1023" height="567" alt="image" src="https://github.com/user-attachments/assets/0f6a67a8-b13e-4d14-ba0d-a6849347a24e" />

---

## 🚀 Tính Năng Chính

- 🎯 **Quiz thời gian thực** với nhiều người chơi
- 🔄 **Cập nhật dữ liệu realtime** bằng Socket.IO
- 👨‍🏫 Hỗ trợ **host / teacher** tạo quiz
- 👨‍🎓 Người chơi tham gia bằng mã phòng
- 🎨 Giao diện hiện đại, **Dark Theme**
- 📱 **Responsive** – hoạt động tốt trên desktop & mobile
- 🧩 Sử dụng Material UI cho giao diện

---

## 🛠️ Công Nghệ Sử Dụng

### 🌐 Frontend
- HTML5, CSS3
- JavaScript (ES6+)
- React
- React Router
- Axios / Fetch API
- Vite
- Material UI

### ⚙️ Backend
- Node.js
- Express.js
- Socket.IO
- MongoDB
- JWT Authentication
- Babel

---

## 📁 Cấu Trúc Thư Mục

```txt
CongNgheWeb20251-QuizzWeb/
├── frontend/
│   ├── landing_page/
│   │   ├── quizzy.html
│   │   └── quizzy.css
│   ├── public/
│   └── src/
│       ├── apis/
│       ├── assets/
│       ├── components/
│       ├── pages/
│       ├── routes/
│       └── main.jsx
│
└── backend/
    ├── src/
    │   ├── controllers/
    │   ├── models/
    │   ├── routes/
    │   └── server.js
    └── package.json
