<h1 align="center">CodeFlow AI</h1>

A modern, AI-powered development platform landing page built with React, Vite, and Tailwind CSS. CodeFlow AI helps developers code faster, build better, and ship production-ready applications 10x faster with intelligent code completion, automated testing, and smart debugging capabilities.

## ✨ Features

### 🤖 AI-Powered Development
- **Smart Code Completion**: Intelligent code suggestions powered by advanced AI that learns from your coding patterns
- **Automated Testing**: Generate comprehensive test suites automatically with unit tests, integration tests, and edge case coverage
- **Smart Debugging**: AI-powered error detection and resolution suggestions to debug faster

### 🎨 Modern UI/UX
- **Interactive Code Showcase**: Live code demonstrations with syntax highlighting
- **Responsive Design**: Fully responsive layout that works seamlessly on all devices
- **Smooth Animations**: Engaging micro-interactions and transitions
- **Dark Theme**: Professional dark theme optimized for developer eyes

### 🛠 Technical Stack
- **Frontend**: React 19 with modern hooks and patterns
- **Build Tool**: Vite for lightning-fast development and building
- **Styling**: Tailwind CSS v4 with custom configurations
- **Icons**: Lucide React for beautiful, consistent icons
- **Code Highlighting**: React Syntax Highlighter with Night Owl theme
- **Linting**: ESLint with React-specific rules

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/codeflow.git
   cd codeflow
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

### Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint to check code quality

## 📁 Project Structure

```
codeflow/
├── public/                 # Static assets
├── src/
│   ├── components/         # React components
│   │   ├── Hero.jsx       # Main hero section with interactive IDE
│   │   ├── Features.jsx   # Feature showcase
│   │   ├── Pricing.jsx    # Pricing plans
│   │   ├── Testimonials.jsx # Customer testimonials
│   │   ├── Navbar.jsx     # Navigation header
│   │   └── Footer.jsx     # Footer section
│   ├── data/              # Static data and configurations
│   │   └── CodeExamples.js # Code snippets for demos
│   ├── assets/            # Images and other assets
│   ├── App.jsx           # Main application component
│   ├── main.jsx          # Application entry point
│   └── index.css         # Global styles
├── package.json          # Dependencies and scripts
├── vite.config.js        # Vite configuration
└── README.md            # This file
```

## 📱 Responsive Design Showcase

CodeFlow AI is built to look stunning on all devices. Our responsive design ensures a perfect experience whether you're on a desktop, tablet, or smartphone.

<div align="center">

### Desktop Experience
![Desktop View](src/assets/Laptop.png)

### Tablet Experience  
![Tablet View](src/assets/iPad%20Air.png)

### Mobile Experience
![Mobile View](src/assets/iPhone%2014%20Pro%20Max.png)

</div>

## 🎯 Key Components

### Hero Section
- Interactive IDE mockup with live code examples
- Mouse-following gradient effects
- Tab-based code demonstration
- Floating feature cards with animations

### Features Section
- Alternating layout with code examples
- Syntax-highlighted code snippets
- Hover effects and smooth transitions
- Responsive design for all screen sizes

### Pricing Section
- Three-tier pricing structure
- "Most Popular" highlighting
- Feature comparison lists
- Call-to-action buttons

## 🛠 Development

### Code Style
- Uses ESLint with React-specific rules
- Modern React patterns with hooks
- Functional components with proper prop handling
- Consistent naming conventions

### Performance Optimizations
- Lazy loading for images
- Optimized animations with CSS transforms
- Efficient re-renders with React hooks
- Minimal bundle size with Vite

### Browser Support
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Android Chrome)

## 🎨 Customization

### Theming
The project uses Tailwind CSS with a dark theme. You can customize colors by modifying the Tailwind configuration in `tailwind.config.js`.

### Code Examples
Update the code snippets in `src/data/CodeExamples.js` to showcase different features or languages.

### Components
Each component is self-contained and can be easily modified:
- Edit component files in `src/components/`
- Update data in `src/data/`
- Modify styles in `src/index.css` or component-specific styles

## 📦 Dependencies

### Production Dependencies
- `react` (^19.2.0) - UI library
- `react-dom` (^19.2.0) - React DOM renderer
- `tailwindcss` (^4.1.17) - Utility-first CSS framework
- `@tailwindcss/vite` (^4.1.17) - Tailwind Vite integration
- `lucide-react` (^0.553.0) - Icon library
- `react-syntax-highlighter` (^15.6.6) - Code syntax highlighting

### Development Dependencies
- `vite` (^7.2.2) - Build tool and dev server
- `@vitejs/plugin-react` (^5.1.0) - React plugin for Vite
- `eslint` (^9.39.1) - Code linting
- `@eslint/js` (^9.39.1) - ESLint configuration
- `globals` (^16.5.0) - Global variables for ESLint
- `@types/react` (^19.2.2) - React TypeScript definitions
- `@types/react-dom` (^19.2.2) - React DOM TypeScript definitions

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Deploy to Vercel
1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect and build the project
3. Your site will be live at `your-project.vercel.app`

### Deploy to Netlify
1. Run `npm run build`
2. Upload the `dist` folder to Netlify
3. Or connect your Git repository for automatic deployments


## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

- © 2025 Haseeb Javed. All rights reserved.


## 🆘 Support

If you have any questions or need help:
- Create an issue on GitHub
- Contact our support team
- Check the documentation

## 🔮 Roadmap

- [ ] Add TypeScript support
- [ ] Implement user authentication
- [ ] Add more code examples
- [ ] Internationalization (i18n)
- [ ] Component library documentation
- [ ] Performance monitoring
- [ ] A/B testing framework

---

**Built with ❤️ by the Haseeb Javed**
