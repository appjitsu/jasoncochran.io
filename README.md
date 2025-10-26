# Jason Cochran - Personal Website

A modern, professional portfolio website showcasing 25 years of software engineering experience.

## 🚀 Quick Start

```bash
cd apps/web
npm install
npm run dev
```

Visit http://localhost:3010

## 📁 Project Structure

```
jason-cochran/
├── apps/
│   └── web/                # Next.js portfolio website
│       ├── app/            # Next.js App Router pages
│       ├── components/     # React components
│       ├── content/        # Blog posts (MDX)
│       ├── lib/            # Utilities
│       └── public/         # Static assets
└── .claude/                # Claude Code configuration
```

## 🛠️ Tech Stack

- **Framework**: Next.js 16 (App Router)
- **React**: 19
- **Language**: TypeScript
- **Styling**: Tailwind CSS 4
- **Blog**: MDX with next-mdx-remote
- **Deployment**: Vercel-ready

## 📄 Pages

- **Homepage** (`/`) - Hero section with animated background, featured case studies
- **Resume** (`/resume`) - Professional experience, skills, certifications
- **Projects** (`/projects`) - Portfolio showcase
- **Blog** (`/blog`) - Technical writing and insights

## 🎨 Features

- ✨ Animated gradient backgrounds
- 🎭 Smooth transitions and hover effects
- 🌓 Dark mode support
- 📱 Fully responsive design
- 🚀 Optimized performance
- 📊 Featured case studies:
  - **Rook** - PSA Platform (320K+ LOC, hexagonal architecture)
  - **WellPulse** - Oil & Gas SaaS (6 apps, offline-first)
  - NFT Collectibles Platform

## 📝 Customization

### Update Your Information

1. **Resume** - Edit `apps/web/app/resume/page.tsx`
2. **Projects** - Edit `apps/web/app/projects/page.tsx`
3. **Homepage** - Edit `apps/web/app/page.tsx`
4. **Photo** - Replace the placeholder in hero section
5. **Blog** - Add `.mdx` files to `apps/web/content/blog/`

### Add Blog Posts

Create a new file in `content/blog/your-post.mdx`:

```mdx
---
title: 'Your Post Title'
date: '2025-10-25'
description: 'Brief description'
tags: ['Tag1', 'Tag2']
---

Your content here...
```

## 🚀 Deployment

### Deploy to Vercel

1. Push to GitHub
2. Import repository in Vercel
3. Deploy (zero configuration needed)

### Build for Production

```bash
cd apps/web
npm run build
npm start
```

## 📜 Scripts

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm start        # Start production server
npm run lint     # Run ESLint
```

## 📧 Contact

- **Email**: jlcochran2013@gmail.com
- **Phone**: (432) 260-7580
- **LinkedIn**: [linkedin.com/in/cochranjason](https://linkedin.com/in/cochranjason)
- **Location**: Midland, TX

## 📄 License

MIT

---

Built with ❤️ using Next.js, React, and Tailwind CSS
