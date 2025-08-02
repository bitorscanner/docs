# Bitor Documentation

This repository contains the official documentation for Bitor, security scanning and automation platform. The documentation is built using [Starlight](https://starlight.astro.build), a documentation framework powered by Astro.

📚 **View the live documentation at [bitor.dev](https://bitor.dev)**

## 🚀 Building Docs Locally

```bash
# Clone the repository
git clone https://github.com/bitorscanner/docs.git
cd docs

# Install dependencies
pnpm install

# Start development server
pnpm dev

# Access the documentation at
http://localhost:4321
```

The development server will automatically reload when you make changes to the documentation files.

## 📖 Documentation Structure

```
docs/
├── src/
│   ├── content/docs/    # Documentation content (MDX files)
│   ├── components/      # Custom components
│   └── styles/          # CSS styles
├── public/             # Static assets
└── astro.config.mjs    # Astro configuration
```

## 🛠️ Available Commands

| Command | Description |
|---------|-------------|
| `pnpm dev` | Start development server with hot reload |
| `pnpm build` | Build documentation for production |
| `pnpm preview` | Preview the production build locally |

### Prerequisites
- Node.js (v18 or later)
- pnpm (v8 or later)

## 🎨 Customization

The documentation uses Tailwind CSS for styling and can be customized through:
- `src/styles/custom.css` - Custom CSS styles
- `tailwind.config.mjs` - Tailwind configuration
- `astro.config.mjs` - Starlight theme configuration

## 🤝 Contributing

We welcome contributions to improve the documentation! Please:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📝 License





