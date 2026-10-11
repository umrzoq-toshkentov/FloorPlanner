# Kvartira 69 m² — 2D/3D planner

Toshkentdagi 69 m² kvartira uchun 2D reja va 3D ko'rinish (neoklassika).
Bitta `index.html` fayl — build kerak emas, brauzerda ochiladi.

- 2D: mebelni sudrab joylashtirish, aylantirish, o'lchash, pol materiallari va narxi
- 3D: aylantirib ko'rish, yurish (walk) rejimi, kun yorug'ligi va tungi yoritish
- Saqlash: brauzerda (localStorage), `File → Export plan JSON` orqali boshqa qurilmaga o'tkazish

Lokal ishga tushirish:

```
python3 -m http.server 8000
# http://localhost:8000
```

Ma'lumotlar `index.html` ichida: `ROOMS`, `WALLS`, `WINS`, `DOORS`, `MATS`, `LIB`, `defaultFurniture()`.

Asos: [wy51ai/floorplan-3d](https://github.com/wy51ai/floorplan-3d) (MIT License).
