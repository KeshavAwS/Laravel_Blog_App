# 🚀 Laravel Blog App

A simple and scalable Blog Application built using the Laravel framework. This project demonstrates core backend development concepts like authentication, CRUD operations, and MVC architecture in Laravel.

## 📌 Features
- 📝 Create, Read, Update, Delete (CRUD) blog posts
- 🔐 User Authentication (Login/Register)
- 🧑‍💼 Role-based access (if implemented)
- 📂 Clean MVC architecture
- 🗃️ Database migrations & seeding
- 🎨 Blade templating engine
- ⚡ Maintainable and scalable code
- 🛠️ **Tech Stack**
      - **Backend**: PHP, Laravel
      - **Frontend**: Blade (HTML, CSS, JS)
      - **Database**: MySQL / SQLite
      - **Tools**: Composer, Artisan CLI
## 📁 Project Structure

```Bash
blog-app/
│
├── app/
│   ├── Models/
│   ├── Http/
│   │   ├── Controllers/
│
├── database/
│   ├── migrations/
│
├── resources/
│   ├── views/
│
├── routes/
│   └── web.php
│
├── public/
├── .env
├── composer.json
└── artisan
```
## ⚙️ Installation & Setup
1️⃣ **Clone the repository**
```Bash
git clone https://github.com/KeshavAwS/Laravel_Blog_App.git
cd Laravel_Blog_App
```
2️⃣ **Install dependencies**
```Bash
composer install
```
3️⃣ **Setup environment file**
```Bash
cp .env.example .env
```
4️⃣ **Generate application key**
```Bash
php artisan key:generate
```
5️⃣ **Configure database**

Update .env file with your database credentials.

6️⃣ **Run migrations**
```Bash
php artisan migrate
```
7️⃣ **Start development server**
```Bash
php artisan serve
```

👉 Open in browser: http://127.0.0.1:8000

🎯 **Future Improvements**
-✅ Categories & tags
-💬 Comment system
-👍 Like / bookmark feature
-🔎 Search & filtering
-🌐 REST API support
-📱 Mobile responsiveness
-🤝 Contributing
**Fork the repository**
**Create a branch (feature/your-feature)**
**Commit your changes**
**Push and open a Pull Request**

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**Keshav Sharma**
🔗 https://github.com/KeshavAwS
