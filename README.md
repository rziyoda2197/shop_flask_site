# shop_flask_site

```
# 🛍️ Flask Shop Web App

Bu kichik Flask asosidagi onlayn do‘kon (shop) loyihasi bo‘lib, mahsulotlar ro‘yxatini ko‘rsatish, ularning tafsilotlarini ko‘rish hamda kontakt sahifasini o‘z ichiga oladi.

## 🚀 Texnologiyalar
- Python 3  
- Flask  
- Flask SQLAlchemy  
- SQLite  

## 📁 Loyihaning tuzilishi


project/
│
├── static/
│   └── uploads/           # Yuklangan rasmlar
├── templates/
│   ├── index.html
│   ├── product_list.html
│   ├── product_detail.html
│   ├── product_add.html
│   └── contact.html
├── shop.py                # Asosiy Flask fayl
└── shop_un.db             # Ma’lumotlar bazasi (avtomatik yaratiladi)



## ⚙️ O‘rnatish

1. **Virtual muhit yaratish va faollashtirish:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
````

2. **Kerakli kutubxonalarni o‘rnatish:**

   ```bash
   pip install flask flask_sqlalchemy
   ```

3. **Dasturini ishga tushirish:**

   ```bash
   python shop.py
   ```

   Brauzerda oching: 👉 `http://127.0.0.1:5000`

## 🧩 Model tuzilmasi

### `Product` modeli

| Ustun nomi    | Turi    | Tavsif              |
| ------------- | ------- | ------------------- |
| id            | Integer | Asosiy kalit        |
| name          | String  | Mahsulot nomi       |
| price         | Float   | Narxi               |
| product_count | Integer | Miqdori (default=1) |
| brend         | String  | Brend nomi          |
| description   | Text    | Tavsif              |
| image         | Text    | Rasm manzili        |

### `Contact` modeli

| Ustun nomi | Turi    | Tavsif              |
| ---------- | ------- | ------------------- |
| id         | Integer | Asosiy kalit        |
| fullname   | String  | Foydalanuvchi F.I.O |
| email      | String  | Elektron pochta     |
| massage    | Text    | Xabar matni         |


Xohlaysizmi, README’ni ingliz tilida yoki yanada soddaroq (masalan, faqat o‘rnatish va ishga tushirish bo‘limlari bilan) variantini ham yozib beray?
```
