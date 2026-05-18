# Nova Frontend

> A modern, powerful note-taking and knowledge management platform built with React and TypeScript, designed for capturing, organizing, and connecting your thoughts, ideas, and information in an intelligent way.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue.svg)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.3-blue.svg)](https://www.typescriptlang.org/)

## 📝 About Nova

Nova is an intelligent note-taking and knowledge management platform that transforms how you capture and organize information. Built for the modern knowledge worker, Nova combines powerful features with an intuitive interface to help you build your personal knowledge base.

Whether you're a student taking lecture notes, a researcher organizing findings, a writer drafting ideas, or a professional managing projects, Nova provides the tools you need to capture, connect, and retrieve information effortlessly.

## 👥 Who Should Use Nova?

### Students
- Take and organize lecture notes efficiently
- Create study guides and flashcards
- Link related concepts across subjects
- Collaborate on group projects
- Prepare for exams with organized materials

### Researchers
- Organize research papers and findings
- Create literature reviews with linked references
- Build knowledge graphs of related concepts
- Annotate and highlight important information
- Export notes in academic formats

### Writers & Content Creators
- Draft articles, stories, and scripts
- Organize research and references
- Create content calendars
- Manage multiple writing projects
- Version control for drafts

### Developers & Technical Professionals
- Document code snippets and solutions
- Create technical documentation
- Organize learning resources
- Build personal wikis
- Track project notes and decisions

### Knowledge Workers
- Capture meeting notes and action items
- Organize project documentation
- Build personal knowledge bases
- Create SOPs and process documentation
- Manage tasks and to-dos

## ✨ Key Features

### Rich Text Editing
- **Markdown Support** - Write in Markdown with live preview
- **WYSIWYG Editor** - Visual editing mode for non-technical users
- **Code Blocks** - Syntax highlighting for 100+ languages
- **Tables** - Create and edit tables easily
- **Embeds** - Embed images, videos, and external content
- **LaTeX Support** - Mathematical equations and formulas
- **Diagrams** - Create flowcharts and diagrams with Mermaid

### Organization & Structure
- **Notebooks** - Group related notes together
- **Folders** - Hierarchical folder structure
- **Tags** - Flexible tagging system
- **Favorites** - Quick access to important notes
- **Archives** - Archive old notes without deleting
- **Workspaces** - Separate personal and work notes

### Linking & Connections
- **Bidirectional Links** - Connect related notes
- **Backlinks** - See all notes linking to current note
- **Graph View** - Visualize connections between notes
- **Mentions** - Reference other notes inline
- **Related Notes** - AI-suggested related content

### Search & Discovery
- **Full-Text Search** - Search across all notes instantly
- **Tag Search** - Filter by tags and combinations
- **Advanced Filters** - Search by date, type, notebook
- **Saved Searches** - Save frequent search queries
- **Quick Jump** - Keyboard-driven navigation

### Collaboration & Sharing
- **Real-Time Collaboration** - Edit notes together
- **Comments** - Add comments and discussions
- **Share Links** - Share notes with public links
- **Permissions** - Control view/edit access
- **Version History** - Track changes over time
- **Export Options** - Export to PDF, Markdown, HTML

### Sync & Backup
- **Cloud Sync** - Automatic sync across devices
- **Offline Mode** - Work without internet
- **Conflict Resolution** - Smart merge for conflicts
- **Automatic Backups** - Daily backups of all notes
- **Export All** - Bulk export functionality

### Templates & Automation
- **Note Templates** - Pre-built templates for common use cases
- **Custom Templates** - Create your own templates
- **Daily Notes** - Automatic daily note creation
- **Quick Capture** - Rapid note creation
- **Shortcuts** - Keyboard shortcuts for efficiency

### Customization
- **Dark Mode** - Beautiful dark theme
- **Custom Themes** - Create your own color schemes
- **Font Options** - Choose your preferred fonts
- **Layout Options** - Customize sidebar and panels
- **Plugins** - Extend functionality with plugins

## 🚀 Getting Started

### Prerequisites
- Node.js 18.x or higher
- npm or yarn package manager
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Pica-code/nova_frontend.git
cd nova_frontend
```

2. **Install dependencies**
```bash
npm install
# or
yarn install
```

3. **Set up environment variables**
```bash
cp .env.example .env
# Edit .env with your configuration
```

4. **Start development server**
```bash
npm run dev
# or
yarn dev
```

5. **Open your browser**
Navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
# or
yarn build
```

The production-ready files will be in the `dist` directory.

## 🛠️ Tech Stack

### Frontend Framework
- **React 18** - Modern UI library with hooks and concurrent features
- **TypeScript 5.3** - Type-safe JavaScript for better development experience
- **Vite** - Lightning-fast build tool and dev server

### Editor & Content
- **React Markdown** - Markdown rendering
- **CodeMirror 6** - Advanced code editor
- **Slate.js** - Rich text editing framework
- **Mermaid** - Diagram and flowchart rendering
- **KaTeX** - LaTeX math rendering

### UI & Styling
- **Tailwind CSS** - Utility-first CSS framework
- **Radix UI** - Accessible component primitives
- **Lucide Icons** - Beautiful icon library
- **Framer Motion** - Smooth animations

### State & Data Management
- **Zustand** - Lightweight state management
- **React Query** - Server state and caching
- **IndexedDB** - Local storage for offline support
- **Immer** - Immutable state updates

### Search & Performance
- **Fuse.js** - Fuzzy search library
- **Virtual Scrolling** - Efficient list rendering
- **Web Workers** - Background processing

### Additional Tools
- **Axios** - HTTP client
- **date-fns** - Date manipulation
- **Zod** - Schema validation
- **React Hook Form** - Form handling

## 📁 Project Structure

```
nova_frontend/
├── src/
│   ├── components/       # Reusable UI components
│   │   ├── editor/      # Editor components
│   │   ├── sidebar/     # Sidebar components
│   │   └── common/      # Common UI elements
│   ├── pages/           # Page components
│   ├── hooks/           # Custom React hooks
│   ├── utils/           # Utility functions
│   ├── services/        # API services
│   ├── stores/          # State management
│   ├── types/           # TypeScript types
│   ├── lib/             # Third-party integrations
│   └── assets/          # Static assets
├── public/              # Public static files
└── tests/              # Test files
```

## 🎯 Development Workflow

### For New Developers

1. **Understand the architecture**
   - Review the component structure
   - Study the state management patterns
   - Understand the editor implementation
   - Review API integration

2. **Set up your environment**
   - Install VS Code with recommended extensions
   - Configure ESLint and Prettier
   - Set up Git hooks with Husky
   - Install React DevTools

3. **Start contributing**
   - Pick an issue from the GitHub issues
   - Create a feature branch
   - Write tests for new features
   - Submit a pull request

4. **Follow best practices**
   - Write TypeScript with strict mode
   - Add JSDoc comments for complex functions
   - Write unit tests for utilities
   - Add integration tests for features
   - Follow the component naming conventions

### For Content Creators & Users

1. **Create your account** and set up your profile
2. **Create your first note** using the "New Note" button
3. **Explore Markdown** - try headings, lists, and formatting
4. **Organize with tags** - add tags to categorize notes
5. **Link notes together** - use [[note name]] to create links
6. **Try templates** - use pre-built templates for common tasks
7. **Customize your workspace** - adjust theme and layout
8. **Enable sync** - sync across your devices

### For Technical Writers

1. **Use Markdown mode** for structured documentation
2. **Create templates** for consistent documentation
3. **Use code blocks** with syntax highlighting
4. **Add diagrams** with Mermaid syntax
5. **Link related docs** to build documentation networks
6. **Export to formats** needed by your team

## 🚢 Deployment

### Vercel (Recommended)
```bash
npm install -g vercel
vercel
```

### Netlify
```bash
npm run build
netlify deploy --prod --dir=dist
```

### Docker
```bash
docker build -t nova-frontend .
docker run -p 3000:3000 nova-frontend
```

### Self-Hosted
```bash
npm run build
# Serve the dist folder with any static server
npx serve dist
```

### Environment Variables
```env
VITE_API_URL=your_api_url
VITE_SYNC_ENABLED=true
VITE_ANALYTICS_ID=your_analytics_id
VITE_STORAGE_BUCKET=your_storage_bucket
```

## 🧪 Testing

```bash
# Run all tests
npm run test

# Run tests in watch mode
npm run test:watch

# Generate coverage report
npm run test:coverage

# Run E2E tests
npm run test:e2e
```

## 🐛 Troubleshooting

### Sync Issues
- Check internet connection
- Verify API endpoint is accessible
- Clear local cache and re-sync
- Check browser console for errors

### Editor Performance
- Reduce number of open notes
- Disable unnecessary plugins
- Clear browser cache
- Update to latest version

### Search Not Working
- Rebuild search index
- Check IndexedDB storage limits
- Clear and re-index notes

### Build Errors
- Delete `node_modules` and reinstall
- Clear Vite cache: `rm -rf node_modules/.vite`
- Verify Node.js version (18.x or higher)
- Check for TypeScript errors

## 🤝 Contributing

We welcome contributions from the community! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting PRs.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Resources & Documentation

- [React Documentation](https://react.dev/)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)
- [Vite Guide](https://vitejs.dev/guide/)
- [React Markdown](https://github.com/remarkjs/react-markdown)
- [Tailwind CSS](https://tailwindcss.com/docs)
- [CodeMirror 6](https://codemirror.net/docs/)
- [Slate.js Documentation](https://docs.slatejs.org/)
- [Mermaid Syntax](https://mermaid.js.org/intro/)
- [KaTeX Documentation](https://katex.org/docs/supported.html)

## 📞 Support & Community

- **GitHub Issues** - Report bugs and request features
- **Discord Community** - Join our community server
- **Documentation** - Comprehensive user guides
- **Email Support** - support@nova-notes.com
- **Twitter** - Follow us @NovaNotesApp

## 🗺️ Roadmap

- [ ] Mobile apps (iOS & Android)
- [ ] Browser extensions
- [ ] API for third-party integrations
- [ ] Advanced AI features
- [ ] Team workspaces
- [ ] End-to-end encryption

---

**Organize your knowledge** 📚 | Built with ❤️ by the Nova Team
