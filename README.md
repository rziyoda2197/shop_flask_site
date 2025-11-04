Albatta 👍
Mana siz README.md faylga **to‘g‘ridan-to‘g‘ri nusxalab qo‘yishingiz mumkin bo‘lgan** toza versiya (Markdown formatida to‘g‘ri chiqadi):

---

```markdown
# shop_flask_site

## 🛍️ Flask Shop Web App

Bu kichik Flask asosidagi onlayn do‘kon (shop) loyihasi bo‘lib, mahsulotlar ro‘yxatini ko‘rsatish, ularning tafsilotlarini ko‘rish hamda kontakt sahifasini o‘z ichiga oladi.

## 🚀 Texnologiyalar
- Python 3  
- Flask  
- Flask SQLAlchemy  
- SQLite  

## 📁 Loyihaning tuzilishi
```

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

````

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

```

---

Xohlasangiz, shu README.md’ga **rasm yoki badge** (masalan, Flask logosi yoki “Made with ❤️ in Python”) ham qo‘shib bezab beray?
```
