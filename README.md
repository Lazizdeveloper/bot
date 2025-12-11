# Telegram PDF Converter Bot

Bu loyiha Telegram bot orqali rasm fayllarini PDF formatiga o'tkazish uchun mo'ljallangan.

## Xususiyatlar:
- JPG, JPEG, HEIC formatlarini qo'llab-quvvatlaydi
- Bir nechta rasmni bitta PDF ga birlashtiradi
- Avtomatik timer bilan ishlaydi (5 soniya)
- Xatoliklarni boshqaradi

## Railway'ga Deploy qilish:

1. **GitHub'ga yuklash:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin YOUR_GITHUB_REPO_URL
   git push -u origin main
   ```

2. **Railway'da:**
   - railway.app ga kiring
   - "New Project" > "Deploy from GitHub repo"
   - Repositoryni tanlang
   - Environment Variables qo'shing:
     - `BOT_TOKEN` = sizning bot tokeningiz

3. **Bot username:** @pidifibot

## Lokal ishlatish:
1. `pip install -r requirements.txt`
2. `BOT_TOKEN` environment variable qo'ying
3. `python bot.py` bilan ishga tushiring