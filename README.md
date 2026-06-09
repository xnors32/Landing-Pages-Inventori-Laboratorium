# Sistem Inventaris Laboratorium - Landing Page

Landing page untuk Sistem Inventaris Laboratorium dengan design system "Clinical Precision" yang telah dikonversi ke teknologi modern.

## 🚀 Tech Stack

- **Vue 3** - Progressive JavaScript framework
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Vite** - Lightning-fast build tool

## 📦 Project Structure

```
├── src/
│   ├── components/
│   │   ├── Header.vue              # Navigation header dengan scroll detection
│   │   ├── HeroSection.vue         # Hero section dengan CTA buttons
│   │   ├── FeaturesSection.vue     # Grid fitur utama (4 cards)
│   │   ├── ArchitectureSection.vue # 3-tier architecture showcase
│   │   ├── TechStackSection.vue    # Technology table
│   │   ├── QuickStartSection.vue   # Developer quickstart terminal
│   │   └── Footer.vue              # Footer dengan links
│   ├── App.vue                     # Root component
│   ├── main.ts                     # Entry point
│   └── index.css                   # Global styles + Tailwind directives
├── index.html                      # HTML entry point
├── vite.config.ts                  # Vite configuration
├── tsconfig.json                   # TypeScript configuration
├── tailwind.config.ts              # Tailwind CSS configuration
├── postcss.config.js               # PostCSS configuration
└── package.json                    # Dependencies
```

## 🎨 Design System

Design system "Clinical Precision" sudah terintegrasi dalam konfigurasi Tailwind:

### Colors
- **Primary**: #091426 (Deep Navy)
- **Secondary**: #006591 (Lab Blue)
- **Surfaces**: Light blue palette untuk clinical feel
- **Semantic Colors**: Success (Green), Warning (Amber), Error (Red)

### Typography
- **Headlines**: Plus Jakarta Sans (600-700 weight)
- **Body**: Inter (400 weight)
- Custom font sizes: headline-xl, headline-lg, body-md, body-sm, label-md

### Components
- **Glass Card**: Glassmorphic effect dengan backdrop blur
- **Terminal Block**: Dark themed code/terminal styling
- **Status Badges**: Semantic colored badges dengan icons
- **Buttons**: Primary (navy), Secondary (white border)

## 💻 Installation & Setup

### Prerequisites
- Node.js 18+ 
- npm atau yarn

### Quick Start

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start development server:**
   ```bash
   npm run dev
   ```
   Aplikasi akan terbuka di `http://localhost:5173`

3. **Build untuk production:**
   ```bash
   npm run build
   ```

4. **Preview build:**
   ```bash
   npm run preview
   ```

## 🔧 Customization

### Mengubah Colors
Edit `tailwind.config.ts` → `theme.extend.colors`

### Mengubah Typography
Edit `tailwind.config.ts` → `theme.extend.fontFamily` dan `fontSize`

### Mengubah Spacing
Edit `tailwind.config.ts` → `theme.extend.spacing`

## 📱 Responsive Design

Project ini fully responsive:
- **Mobile**: 4-column grid, margin-mobile (16px)
- **Desktop**: 12-column grid, margin-desktop (40px)
- Breakpoint: `md` (768px)

## 🎯 Features

✅ Clinical Precision Design System  
✅ Fully Responsive (Mobile & Desktop)  
✅ TypeScript untuk type safety  
✅ Vue 3 Composition API  
✅ Smooth animations & transitions  
✅ Glassmorphic UI components  
✅ Material Symbols integration  
✅ Production-ready code  

## 📄 Sections

1. **Header** - Fixed navigation dengan scroll detection
2. **Hero** - Large heading dengan CTA buttons
3. **Features** - 4-card grid dengan icons
4. **Architecture** - 3-tier architecture showcase
5. **Tech Stack** - Interactive table dengan status badges
6. **Quick Start** - Terminal mockup dengan commands
7. **Footer** - Navigation links dan copyright

## 🚀 Deployment

### Vercel
```bash
npm run build
# Push ke repository, Vercel akan auto-deploy
```

### Netlify
```bash
npm run build
# Drag & drop dist folder ke Netlify
```

### Docker
```dockerfile
FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build
EXPOSE 3000
CMD ["npm", "run", "preview"]
```

## 📚 Resources

- [Vue 3 Docs](https://vuejs.org)
- [Tailwind CSS Docs](https://tailwindcss.com)
- [Vite Docs](https://vitejs.dev)
- [TypeScript Docs](https://www.typescriptlang.org)

## 📝 License

© 2024 Sistem Inventaris Laboratorium. All rights reserved.

---

**Happy Coding! 🎉**
# Landing-Pages-Inventori-Laboratorium
# Landing-Pages-Inventori-Laboratorium
