# 👟 ShkeelShoes - E-Commerce SaaS Platform

[![Laravel 12](https://img.shields.io/badge/Laravel-12.0-red.svg)](https://laravel.com)
[![Vue.js 3](https://img.shields.io/badge/Vue.js-3.4-green.svg)](https://vuejs.org)
[![Tailwind 4](https://img.shields.io/badge/Tailwind-4.0-blue.svg)](https://tailwindcss.com)

Platformë profesionale E-Commerce SaaS e ndërtuar me stack-un më modern (Laravel 12, Vue 3, Inertia.js v2, Tailwind 4).

## 🚀 Karakteristikat
- **Full SPA Experience**: Tranzicione të shpejta me Inertia.js.
- **Admin Dashboard**: Menaxhim i plotë i produkteve, porosive dhe klientëve.
- **Performance**: Cache me Redis, Eager Loading, dhe optimizim i queries.
- **Security**: Rate limiting, Session encryption, dhe Role-based access control.
- **SEO Ready**: Meta tags dinamike dhe Open Graph support.

## 🛠 Instalimi

1. **Clone repository:**
   ```bash
   git clone https://github.com/your-username/shkeelshoes.git
   cd shkeelshoes
   ```

2. **Backend Setup:**
   ```bash
   composer install
   cp .env.example .env
   php artisan key:generate
   php artisan storage:link
   ```

3. **Frontend Setup:**
   ```bash
   npm install
   npm run dev
   ```

4. **Database Migration:**
   ```bash
   php artisan migrate --seed
   ```

## 📋 Pre-Deployment Checklist (20 Pika)
- [ ] APP_ENV=production
- [ ] APP_DEBUG=false
- [ ] APP_KEY i gjeneruar
- [ ] SESSION_DRIVER=redis/database (jo file)
- [ ] CACHE_STORE=redis
- [ ] QUEUE_CONNECTION=redis
- [ ] Optimize loading: `php artisan optimize`
- [ ] SSL Certificate (HTTPS)
- [ ] Rate limiting i aktivizuar
- [ ] Monitoring (Sentry ose Health checks)
- [ ] Database backups të automatizuara
- [ ] Image optimization (WebP)
- [ ] Minify CSS/JS (Vite build)
- [ ] Mail server (Resend/Mailgun) i konfiguruar
- [ ] SEO Meta tags të verifikuara
- [ ] Robots.txt i konfiguruar
- [ ] Favicon i vendosur
- [ ] Testet kalojnë (`php artisan test`)
- [ ] Error pages (404, 500) të personalizuara
- [ ] Security headers (CSP, HSTS)

## 📄 Licenca
Ky projekt është proprietar. Të gjitha të drejtat e rezervuara.
