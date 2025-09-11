# Code Journey Portfolio 🚀

An interactive, terminal-themed portfolio website that transforms from a command-line interface into a rich visual experience through scroll-based animations and interactions.

![Portfolio Preview](https://via.placeholder.com/800x400/282a36/f8f8f2?text=Code+Journey+Portfolio)

## ✨ Features

### 🖥️ Terminal Interface
- **Boot Sequence Animation**: Realistic system initialization with loading progress
- **Interactive Terminal**: Functional command-line interface with custom commands
- **Matrix Rain Effect**: Dynamic background with code snippets and characters
- **ASCII Art Logo**: Animated transformation from ASCII to modern typography

### 🎨 Modern UI/UX
- **Code-to-Text Transformation**: About section morphs from syntax-highlighted code to readable content
- **3D Skills Visualization**: Interactive network graph showing technology relationships
- **Git History Timeline**: Project showcase with commit history and development progress
- **API Documentation Style**: Contact form styled as REST API endpoint

### 🎭 Advanced Animations
- **Framer Motion**: Smooth page transitions and micro-interactions
- **GSAP ScrollTrigger**: Complex scroll-based animations
- **Three.js Integration**: 3D graphics and interactive visualizations
- **Responsive Design**: Optimized for all device sizes

### 🎯 Interactive Elements
- **Command Palette**: Quick navigation with Cmd/Ctrl+K
- **Theme System**: Multiple IDE-inspired color schemes
- **Scroll Progress**: Visual indicator and smooth navigation
- **Hover Effects**: Dynamic feedback throughout the interface

## 🛠️ Tech Stack

### Core Technologies
- **Next.js 14+** - React framework with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **React 18+** - Latest React features

### Animation & 3D
- **Framer Motion** - Production-ready motion library
- **GSAP** - Professional animation toolkit
- **Three.js** - 3D graphics library
- **React Three Fiber** - React renderer for Three.js

### UI Components
- **React Hook Form** - Form validation and handling
- **React Hot Toast** - Notification system
- **React Syntax Highlighter** - Code syntax highlighting
- **Zustand** - State management

### Development Tools
- **ESLint** - Code linting
- **Prettier** - Code formatting
- **TypeScript** - Static type checking

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm, yarn, or pnpm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ghulam-shabbir/code-journey-portfolio.git
   cd code-journey-portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open in browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
src/
├── app/                    # Next.js App Router
│   ├── globals.css        # Global styles and CSS variables
│   ├── layout.tsx         # Root layout component
│   └── page.tsx           # Main page component
├── components/            # React components
│   ├── Hero/              # Terminal interface and boot sequence
│   ├── About/             # Code-to-text transformation
│   ├── Skills/            # 3D skills visualization
│   ├── Projects/          # Project showcase with git history
│   ├── Experience/        # Professional timeline
│   ├── Contact/           # API-style contact form
│   └── common/            # Shared components (Navigation, etc.)
├── hooks/                 # Custom React hooks
│   ├── useTheme.ts        # Theme management
│   ├── useTerminal.ts     # Terminal functionality
│   ├── useScrollProgress.ts # Scroll tracking
│   └── useAnimationTrigger.ts # Animation triggers
├── lib/                   # Utility functions
│   ├── animations.ts      # Framer Motion variants
│   ├── constants.ts       # App constants
│   └── utils.ts           # Helper functions
├── styles/                # Styling
│   └── themes/            # Theme definitions
└── data/                  # Static data
    ├── projects.json      # Project information
    ├── skills.json        # Skills and technologies
    └── experience.json    # Work experience
```

## 🎨 Customization

### Themes
The portfolio includes 5 built-in themes:
- **Dracula** (default)
- **Monokai**
- **Solarized Dark**
- **GitHub Dark**
- **VS Code Dark**

Add new themes in `src/styles/themes/index.ts`:

```typescript
export const customTheme: Theme = {
  name: 'Custom Theme',
  colors: {
    primary: '#your-color',
    // ... other colors
  }
};
```

### Content
Update your information in the data files:
- `src/data/projects.json` - Your projects
- `src/data/skills.json` - Your skills and technologies  
- `src/data/experience.json` - Your work experience

### Terminal Commands
Add custom terminal commands in `src/hooks/useTerminal.ts`:

```typescript
case 'your-command':
  addLine('Your custom response', 'output');
  break;
```

## 🔧 Configuration

### Environment Variables
Create a `.env.local` file:

```env
NEXT_PUBLIC_EMAIL_SERVICE_ID=your_email_service_id
NEXT_PUBLIC_EMAIL_TEMPLATE_ID=your_template_id
NEXT_PUBLIC_EMAIL_PUBLIC_KEY=your_public_key
NEXT_PUBLIC_GA_ID=your_google_analytics_id
```

### Performance Optimization
The portfolio is optimized for performance with:
- Code splitting and lazy loading
- Image optimization
- Bundle size optimization
- Efficient animations using GPU acceleration

## 📱 Browser Support
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Android)

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically on every push

### Other Platforms
- **Netlify**: Drag and drop the `out` folder after `npm run build`
- **GitHub Pages**: Use GitHub Actions for automated deployment
- **Railway**: Connect your repository for automatic deployment

### Build Commands
```bash
# Production build
npm run build

# Start production server
npm run start

# Export static files
npm run export
```

## 🎯 Performance Benchmarks
- Lighthouse Performance: 90+
- First Contentful Paint: <1.5s
- Time to Interactive: <3.5s
- Cumulative Layout Shift: <0.1

## 🤝 Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments
- [Next.js](https://nextjs.org/) - The React framework
- [Framer Motion](https://www.framer.com/motion/) - Animation library
- [Three.js](https://threejs.org/) - 3D graphics
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework
- [Dracula Theme](https://draculatheme.com/) - Color scheme inspiration

## 📞 Contact
- **Email**: ghulam.shabbir@example.com
- **LinkedIn**: [linkedin.com/in/ghulam-shabbir](https://linkedin.com/in/ghulam-shabbir)
- **GitHub**: [github.com/ghulam-shabbir](https://github.com/ghulam-shabbir)

---

**Built with ❤️ by Ghulam Shabbir**
