# Apex Architecture - Premium Qurilish Kompaniyasi

Ushbu loyiha zamonaviy arxitektura va qurilish kompaniyasi uchun ishlab chiqilgan yuqori darajadagi web-sayt. Sayt Next.js, TypeScript va Tailwind CSS texnologiyalari asosida qurilgan bo'lib, to'liq statik rejimda (backend-siz) ishlaydi va GitHub Pages kabi platformalarga joylashtirishga moslashtirilgan.

## Xususiyatlar

- **Premium Dizayn:** Zamonaviy, "glassmorphism" va nozik animatsiyalar bilan boyitilgan UI.
- **Statik Eksport:** `next export` orqali to'liq statik HTML/CSS/JS fayllar yaratiladi.
- **Responsive:** Barcha qurilmalarda (mobil, planshet, desktop) ideal ko'rinish.
- **GitHub Actions:** Avtomatik joylashtirish (CI/CD) sozlamalari mavjud.

## Texnologiyalar

- [Next.js](https://nextjs.org/)
- [React](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)

## O'rnatish va Ishga Tushirish

Loyihani lokal kompyuterda ishga tushirish uchun:

1. **Repozitoriyni klonlash:**
   ```bash
   git clone https://github.com/sizning-username/Architecture-new.git
   cd Architecture-new
   ```

2. **Kutubxonalarni o'rnatish:**
   ```bash
   npm install
   ```

3. **Lokal serverni yoqish:**
   ```bash
   npm run dev
   ```
   Brauzerda `http://localhost:3000` manzilini oching.

## Deploy (GitHub Pages)

Ushbu loyiha GitHub Actions yordamida GitHub Pages ga avtomatik joylashishga sozlangan.

1. Loyihani GitHub ga yuklang (Push).
2. GitHub repozitoriysida **Settings** -> **Pages** bo'limiga o'ting.
3. **Build and deployment** bo'limida **Source** ni **GitHub Actions** ga o'zgartiring.
4. Biroz kutib turing, Actions loyihani quradi va saytni e'lon qiladi.

## Litsenziya

MIT
