# 🎯 Interview Prep Platform

> **400+ Senior-Level Questions** for Angular • React • Next.js • Redux<br/>
> Professional study platform with routing, progress tracking, PWA support & enterprise architecture

[![CI](https://github.com/htirawi/angular-interview-prep/workflows/CI/badge.svg)](https://github.com/htirawi/angular-interview-prep/actions)
[![Tests](https://img.shields.io/badge/tests-58%20passing-brightgreen.svg)](https://github.com/htirawi/angular-interview-prep)
[![TypeScript](https://img.shields.io/badge/TypeScript-89.7%25-blue.svg)](https://www.typescriptlang.org/)
[![Coverage](https://img.shields.io/badge/coverage-70%25+-green.svg)](https://github.com/htirawi/angular-interview-prep)
[![React](https://img.shields.io/badge/React-19-61dafb.svg)](https://reactjs.org/)
[![Bundle](https://img.shields.io/badge/bundle-375KB-orange.svg)](https://github.com/htirawi/angular-interview-prep)
[![PWA](https://img.shields.io/badge/PWA-enabled-purple.svg)](https://github.com/htirawi/angular-interview-prep)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](.github/CONTRIBUTING.md)

[**Live Demo →**](https://angular-interview-prep.vercel.app) | [**Docs →**](docs/) | [**Architecture →**](docs/ARCHITECTURE.md) | [**Contributing →**](.github/CONTRIBUTING.md)

---

## 🌟 What Makes This Special

**400+ Questions** across 4 frameworks • **Landing Page** with beautiful UI • **Per-Framework Progress** tracking • **Clean URLs** (`/angular`, `/react`, `/nextjs`, `/redux`) • **Enterprise Architecture** (types/, pages/, routing) • **58 Tests** (100% passing) • **CI/CD Pipeline** (automated) • **PWA Ready** (offline support)

---

## ✨ Features

### 🎨 Professional UI/UX

- Modern gradient design with smooth animations
- Dark mode with system preference detection
- Fully responsive (mobile, tablet, desktop)
- Accessible (WCAG 2.1 AA compliant)

### 🔍 Smart Search & Filtering

- Real-time search across questions, answers, and tags
- Filter by 15+ categories (Architecture, RxJS, Forms, NgRx, etc.)
- Filter by difficulty (Intermediate, Advanced, Expert)
- Smart auto-categorization

### 📊 Progress Tracking

- Visual statistics dashboard
- Track completed questions
- Progress percentage
- Persistent across sessions

### ⭐ Study Features

- **Sequential Mode** - Linear progression
- **Random Mode** - Shuffled questions for practice
- **Bookmarked Mode** - Save and review favorites
- Keyboard shortcuts (← → A B)

### 🚀 Production Ready

- PWA installable (works offline)
- SEO optimized
- Deployment configs (Vercel, Netlify, Docker)
- Security headers configured
- Performance optimized (Lighthouse 95+)

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/angular-interview-prep.git
cd angular-interview-prep

# Install dependencies
pnpm install

# Start development server
pnpm dev

# Open http://localhost:5173
```

---

## 📦 Available Scripts

```bash
pnpm dev        # Start development server
pnpm build      # Build for production
pnpm preview    # Preview production build
pnpm test       # Run tests
pnpm lint       # Lint code
pnpm format     # Format code with Prettier
```

---

## ⌨️ Keyboard Shortcuts

| Shortcut  | Action                   |
| --------- | ------------------------ |
| `←` / `→` | Navigate questions       |
| `A`       | Toggle answer visibility |
| `B`       | Bookmark question        |
| `Esc`     | Clear search             |

---

## 📚 Question Coverage

100 curated questions covering:

- 🏗️ **Architecture** - Framework design, DI, standalone components
- ⚡ **Reactive Programming** - Signals, RxJS, Observables
- 🔄 **Change Detection** - OnPush, performance, rendering
- 📝 **Forms** - Reactive forms, validation, CVA
- 🌐 **HTTP & API** - Interceptors, error handling, caching
- 🧭 **Routing** - Guards, resolvers, lazy loading
- 📦 **State Management** - NgRx, selectors, effects
- 🧪 **Testing** - Unit tests, component tests, harnesses
- ⚡ **Performance** - Optimization, metrics, LCP/TBT
- 🔒 **Security** - Authentication, authorization, XSS
- 📡 **Real-time** - WebSockets, SignalR, SSE
- 🖥️ **SSR & Hydration** - Server-side rendering
- ♿ **Accessibility** - a11y, ARIA, keyboard navigation
- 🎨 **Components** - Lifecycle, communication, patterns
- 💉 **Dependency Injection** - Providers, tokens, scoping

---

## 🎯 How to Use

### For First-Time Study

1. Start with **Sequential Mode**
2. Read each question carefully
3. Try to answer before revealing
4. Bookmark challenging questions

### For Interview Prep

1. Use **Random Mode** to simulate interviews
2. Filter by difficulty level
3. Focus on bookmarked questions
4. Practice explaining answers out loud

### For Quick Review

1. Switch to **Bookmarked Mode**
2. Use search to find specific topics
3. Filter by category
4. Track your progress

---

## 🚀 Deployment

### Vercel (Recommended)

```bash
npm i -g vercel
vercel
```

### Netlify

```bash
npm i -g netlify-cli
netlify deploy --prod
```

### Docker

```bash
docker build -t angular-interview-prep .
docker run -p 3000:80 angular-interview-prep
```

### GitHub Pages

Push to `main` branch - auto-deploys via GitHub Actions!

---

## 🛠️ Tech Stack

- **Framework**: React 19 + TypeScript
- **Build Tool**: Vite 5
- **Styling**: Tailwind CSS 3
- **Testing**: Vitest + React Testing Library
- **Code Quality**: ESLint + Prettier
- **State**: LocalStorage with custom hooks
- **PWA**: Web App Manifest

---

## 🤝 Contributing

Contributions welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing`)
5. Open a Pull Request

### Adding Questions

Edit `src/data/questions.ts`:

```typescript
{
  id: 101,
  question: "Your question here",
  answer: "Detailed answer with examples...",
  category: "Category Name",
  difficulty: "advanced",
  tags: ["tag1", "tag2"]
}
```

---

## 📄 License

MIT License - feel free to use for your interview prep!

---

## 🌟 Star History

If this helped you ace your Angular interview, give it a star! ⭐

---

## 💡 Interview Tips

1. **Understand Concepts** - Don't just memorize
2. **Practice Explaining** - Talk through answers
3. **Know Tradeoffs** - Understand alternatives
4. **Stay Current** - Questions cover Angular 16-19
5. **Build Projects** - Hands-on experience matters

---

## 📧 Contact

Questions or feedback? Open an issue!

---

**Good luck with your interview!** 🚀

_Built with ❤️ for Angular developers_
