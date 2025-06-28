# CodinIT.dev Documentation

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/codinit-dev/codinit-docs)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/codinit-dev/codinit-docs)
[![Better Stack Badge](https://uptime.betterstack.com/status-badges/v1/monitor/1zjhs.svg)](https://uptime.betterstack.com/?utm_source=status_badge)

Official documentation for [CodinIT.dev](https://codinit.dev) - the open-source AI-powered app builder platform.

## 🚀 About CodinIT.dev

CodinIT.dev is an AI-powered platform that enables users of any skill level to create full-stack web applications without requiring coding expertise. Simply describe what you want in plain English, and our AI will build, deploy, and help you edit your applications.

### Key Features

- 🤖 **AI-Powered Development** - Build apps using natural language
- 🔒 **Secure Sandboxes** - Powered by [e2b.dev](https://e2b.dev) for safe code execution
- 🌐 **Full-Stack Capable** - Frontend, backend, databases, and deployment
- 🔄 **Real-Time Collaboration** - Work with your team in shared workspaces
- 🎨 **Visual Editing** - Edit components with AI assistance
- 📦 **One-Click Deploy** - Deploy instantly with custom domains
- 🔓 **Open Source** - Self-host and customize as needed

### Content Organization

```
content/
├── 1.getting-started/     # Getting started guides
├── 2.essentials/          # Core concepts and features
├── 3.models/              # AI model configurations
├── 4.providers/           # AI provider integrations
└── index.md               # Landing page
```

## 🛠️ Development Setup

### Prerequisites

- Node.js 18+ 
- pnpm 8+ (recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Gerome-Elassaad/docs.git
   cd codinit-docs
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

4. **Start development server**
   ```bash
   pnpm dev
   ```

5. **Open your browser**
   Visit [http://localhost:3000](http://localhost:3000)

### Available Scripts

```bash
# Development
pnpm dev                # Start development server
pnpm build              # Build for production
pnpm preview            # Preview production build
pnpm generate           # Generate static site

# Code Quality
pnpm lint               # Run ESLint
pnpm lint:fix           # Fix ESLint issues
pnpm typecheck          # Run TypeScript checks

# Testing
pnpm test               # Run tests
pnpm test:ui            # Run tests with UI

# Maintenance
pnpm clean              # Clean build artifacts
```

## 📝 Contributing

We welcome contributions to improve the documentation! Here's how you can help:

### Content Guidelines

1. **Write Clear Content**
   - Use simple, accessible language
   - Include practical examples
   - Structure content with clear headings

2. **Follow Markdown Standards**
   - Use consistent formatting
   - Include code examples with syntax highlighting
   - Add alt text for images

3. **Test Your Changes**
   - Run the development server locally
   - Check for broken links
   - Verify responsive design

### Contribution Process

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b docs/your-feature-name
   ```
3. **Make your changes**
4. **Test locally**
   ```bash
   pnpm dev
   ```
5. **Submit a pull request**

### Content Types

- **Guides**: Step-by-step tutorials
- **References**: API documentation and technical specs
- **Examples**: Code samples and use cases
- **Troubleshooting**: Common issues and solutions

## 🎨 Customization

### Theming

The documentation uses a custom theme based on CodinIT.dev branding:

```css
/* Primary colors */
--color-blue-500: #3B82F6;    /* CodinIT blue */
--color-purple-500: #A855F7;  /* AI accent */

/* Fonts */
--font-sans: 'Inter', system-ui, sans-serif;
--font-mono: 'JetBrains Mono', monospace;
```

### Components

Custom components are available in `components/` directory:

- `ProseComponents` - Enhanced markdown components
- `CodeBlocks` - Syntax highlighted code examples
- `Navigation` - Dynamic sidebar navigation
- `Search` - Full-text search functionality

## 🚀 Deployment

### Vercel (Recommended)

1. **Connect your repository** to Vercel
2. **Set environment variables** in Vercel dashboard
3. **Deploy** - Automatic deployments on push to main

### Netlify

1. **Connect your repository** to Netlify
2. **Configure build settings**:
   - Build command: `pnpm generate`
   - Publish directory: `dist`
3. **Set environment variables**
4. **Deploy**

### Self-Hosted

```bash
# Build for production
pnpm generate

# Serve static files with any web server
# Example with nginx, apache, or node static server
```

## 📊 Analytics & Monitoring

The documentation supports various analytics providers:

- **Google Analytics** - Web analytics
- **Umami** - Privacy-focused analytics  
- **Plausible** - Simple web analytics
- **Vercel Analytics** - Performance monitoring

Configure in your `.env` file:

```bash
NUXT_GOOGLE_ANALYTICS_ID=your-ga-id
NUXT_UMAMI_SITE_ID=your-umami-id
NUXT_PLAUSIBLE_DOMAIN=docs.codinit.dev
```

## 🔍 Search & SEO

### Search Features

- **Full-text search** powered by Fuse.js
- **Keyboard shortcuts** (⌘K / Ctrl+K)
- **Scoped search** by section
- **Search highlighting**

### SEO Optimization

- **Structured data** with Schema.org
- **Open Graph** meta tags
- **Twitter Cards** support
- **Sitemap** generation
- **Canonical URLs**

## 🤝 Community & Support

### Getting Help

- 📖 [Documentation](https://docs.codinit.dev)
- 🐛 [GitHub Issues](https://github.com/Gerome-Elassaad/docs/issues)
- 🐦 [Twitter](https://x.com/codinit_dev)

### Contributing to CodinIT.dev

Interested in contributing to the main platform?

- 🌟 [CodinIT.dev Repository](https://github.com/Gerome-Elassaad/codingit)
- 🏗️ [e2b.dev Sandboxes](https://e2b.dev)
- 📋 [Feature Requests](https://github.com/codinit-dev/codinit/discussions)

## 📄 License

This documentation is licensed under the [MIT License](LICENSE).

The CodinIT.dev platform is open-source and available under the [MIT License](https://github.com/codinit-dev/codinit/blob/main/LICENSE).

---

**Built with ❤️ by the CodinIT.dev team**

Powered by [e2b.dev](https://e2b.dev) sandboxes for secure AI code execution.