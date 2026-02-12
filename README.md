# AI-Powered UI Generator

A sophisticated Next.js 14+ application featuring a multi-agent AI system for intelligent UI generation with component library management, real-time preview, and version control.

![AI-Powered UI Generator](https://img.shields.io/badge/Next.js-14+-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-18+-blue?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.3+-blue?style=for-the-badge&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4+-38B2AC?style=for-the-badge&logo=tailwind-css)

## 🌟 Features

### Multi-Agent AI System
- **Planner Agent**: Analyzes requirements and creates structured implementation plans
- **Designer Agent**: Generates design specifications, layouts, and styling recommendations
- **Developer Agent**: Produces production-ready React/Next.js code
- **Validator Agent**: Ensures code quality, accessibility, and best practices

### Component Library Management
- Pre-built, customizable component library (Button, Card, Input, Modal, etc.)
- Component preview and documentation
- Drag-and-drop component insertion
- Real-time component customization

### 3-Panel Interface
- **Left Panel**: Component library and AI agent controls
- **Center Panel**: Monaco code editor with syntax highlighting
- **Right Panel**: Live preview with responsive device simulation

### Version Control
- Git-like versioning system
- Commit history with timestamps
- Branch management
- Rollback to previous versions
- Diff viewer

### Advanced Features
- Real-time code validation and linting
- Export to multiple formats (HTML, React, Next.js)
- Responsive design preview (Desktop, Tablet, Mobile)
- Dark/Light theme support
- Keyboard shortcuts for power users

## 🚀 Getting Started

### Prerequisites

- Node.js 18.0 or higher
- npm 9.0 or higher
- OpenAI API key (for AI features)

### Installation

1. Clone the repository:
\`\`\`bash
git clone https://github.com/yourusername/ai-powered-ui-generator.git
cd ai-powered-ui-generator
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
\`\`\`

3. Set up environment variables:
\`\`\`bash
cp .env.example .env.local
\`\`\`

4. Add your OpenAI API key to `.env.local`:
\`\`\`
OPENAI_API_KEY=your_api_key_here
\`\`\`

5. Run the development server:
\`\`\`bash
npm run dev
\`\`\`

6. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📖 Usage Guide

### Basic Workflow

1. **Enter Requirements**: Type your UI requirements in the prompt input
2. **AI Generation**: The multi-agent system analyzes and generates code
3. **Preview & Edit**: View real-time preview and edit code as needed
4. **Version Control**: Commit changes to track your progress
5. **Export**: Download your generated UI in your preferred format

### Using Component Library

1. Browse components in the left sidebar
2. Click on a component to view details
3. Drag and drop or click "Insert" to add to editor
4. Customize component props in the code editor

### Version Control Operations

- **Commit**: Save current state with a message
- **View History**: Browse all commits with timestamps
- **Rollback**: Restore previous versions
- **Compare**: View differences between versions

## 📁 Project Structure

\`\`\`
ai-powered-ui-generator/
├── src/
│   ├── app/
│   │   ├── page.tsx                 # Main application page
│   │   ├── layout.tsx               # Root layout
│   │   ├── globals.css              # Global styles
│   │   └── api/
│   │       └── generate/
│   │           └── route.ts         # AI generation API endpoint
│   ├── components/
│   │   ├── Header.tsx               # Top navigation bar
│   │   ├── Sidebar.tsx              # Left sidebar with components
│   │   ├── MainPanel.tsx            # Center code editor panel
│   │   ├── CodeEditor.tsx           # Monaco editor wrapper
│   │   ├── PreviewPanel.tsx         # Right preview panel
│   │   ├── ComponentLibrary.tsx     # Component browser
│   │   ├── VersionControl.tsx       # Version control UI
│   │   ├── AIAgentPanel.tsx         # Agent status display
│   │   └── ExportDialog.tsx         # Export functionality
│   ├── lib/
│   │   ├── agents/
│   │   │   ├── plannerAgent.ts      # Planner AI agent
│   │   │   ├── designerAgent.ts     # Designer AI agent
│   │   │   ├── developerAgent.ts    # Developer AI agent
│   │   │   ├── validatorAgent.ts    # Validator AI agent
│   │   │   └── agentOrchestrator.ts # Agent coordination
│   │   ├── componentLibrary.ts      # Component definitions
│   │   ├── versionControl.ts        # Version control logic
│   │   ├── codeGenerator.ts         # Code generation utilities
│   │   └── utils.ts                 # Helper functions
│   ├── types/
│   │   └── index.ts                 # TypeScript type definitions
│   └── hooks/
│       ├── useUIGenerator.ts        # Main UI generation hook
│       └── useVersionControl.ts     # Version control hook
├── public/
│   └── logo.svg                     # Application logo
├── package.json                     # Dependencies
├── next.config.js                   # Next.js configuration
├── tsconfig.json                    # TypeScript configuration
├── tailwind.config.js               # Tailwind CSS configuration
└── README.md                        # This file
\`\`\`

## 🛠️ Technology Stack

- **Framework**: Next.js 14+ (App Router)
- **UI Library**: React 18+
- **Language**: TypeScript 5.3+
- **Styling**: Tailwind CSS 3.4+
- **Code Editor**: Monaco Editor
- **AI**: OpenAI GPT-4
- **State Management**: Zustand
- **Icons**: Lucide React
- **Animations**: Framer Motion

## 🎨 Component Library

The application includes a comprehensive component library:

- **Layout**: Container, Grid, Flex, Stack
- **Forms**: Input, Textarea, Select, Checkbox, Radio
- **Buttons**: Button, IconButton, ButtonGroup
- **Data Display**: Card, Table, List, Badge, Avatar
- **Feedback**: Alert, Toast, Progress, Spinner
- **Navigation**: Navbar, Tabs, Breadcrumb, Pagination
- **Overlay**: Modal, Drawer, Tooltip, Popover

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Next.js team for the amazing framework
- OpenAI for the GPT-4 API
- Monaco Editor for the code editor
- The open-source community

## 📞 Support

For issues, questions, or suggestions:
- Open an issue on GitHub
- Email: support@aiuigenerator.com
- Twitter: @aiuigenerator

---

Built with Aakshin C S ❤️ using Next.js and AI
