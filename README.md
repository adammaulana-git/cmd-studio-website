# CMD Studio Website

Landing page untuk CMD Studio - Digital Solutions for Modern Business

## 🚀 Stack

- **Next.js 14** - React framework untuk production
- **GitHub Pages** - Static hosting
- **GitHub Actions** - CI/CD automation

## 📦 Setup Lokal (Opsional)

```bash
# Clone repository
git clone https://github.com/adammaulana-git/cmd-studio-website.git
cd cmd-studio-website

# Install dependencies
npm install

# Run development server
npm run dev
```

Buka [http://localhost:3000](http://localhost:3000) untuk preview.

## 🏗️ Build & Deploy

### Development
```bash
npm run dev      # Run local server
npm run lint     # Check code quality
```

### Production
```bash
npm run build    # Build Next.js project
npm run export   # Export ke static files
npm run start    # Start production server
```

## 🔄 Deployment (GitHub Pages)

Deployment **otomatis** melalui GitHub Actions workflow (`.github/workflows/deploy.yml`):

1. Setiap push ke branch `main` akan trigger workflow
2. Build Next.js project
3. Export ke static files
4. Deploy ke GitHub Pages branch (`gh-pages`)

**Live URL:** https://adammaulana-git.github.io/cmd-studio-website/

## 📂 Project Structure

```
app/
  layout.js       # Root layout
  page.js         # Home page
public/           # Static assets
.github/
  workflows/
    deploy.yml    # GitHub Pages deployment workflow
package.json      # Dependencies & scripts
next.config.js    # Next.js configuration
```

## 🛠️ Environment Variables

Tidak ada environment variables yang diperlukan untuk saat ini.

## 📝 Development Guide

- Edit components di folder `app/`
- Tambahkan static assets ke folder `public/`
- Push ke `main` branch untuk deploy otomatis
- Preview live di https://adammaulana-git.github.io/cmd-studio-website/

## 📄 License

MIT

---

**Last Updated:** September 2026
