# ⚛️ QuantumLearn

### Learn Quantum Computing. Understand Quantum Algorithms. Explore the Future.

**QuantumLearn** is an interactive quantum computing learning platform designed to make quantum computing and quantum algorithms more approachable for learners and developers.

The project aims to provide a structured digital learning experience for exploring the concepts behind quantum computing.

🌐 **Live Platform:** [quantlearn-new.vercel.app](https://quantlearn-new.vercel.app/onboarding)

📦 **GitHub Repository:** [quantlearn-new](https://github.com/parmeshwarvarfa-dot/quantlearn-new)

---

## 🎯 Project Overview

Quantum computing is an emerging field that combines mathematics, computer science and quantum physics to introduce new approaches to computation.

QuantumLearn aims to make this field easier to explore through a dedicated learning platform focused on quantum computing and quantum algorithms.

The goal is to create an accessible environment where learners can develop their understanding of quantum concepts and explore the technologies shaping the future of computing.

## ✨ Project Highlights

- **Quantum Computing Education** – A dedicated platform focused on learning quantum computing.
- **Quantum Algorithms** – A learning experience centered around understanding quantum algorithms.
- **Modern Web Architecture** – Built using a modern TypeScript-based technology stack.
- **Scalable Foundation** – Organized as a modular monorepo to support future development.
- **AI Integration Infrastructure** – Includes an AI-related API workspace in the project structure.

*Note: This section describes the project's focus and architecture, not a guarantee that every planned learning feature is already implemented.*

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| TypeScript | Type-safe development |
| Node.js 24 | JavaScript runtime |
| React 19 | User interface |
| Vite 7 | Development and build tooling |
| Tailwind CSS 4 | Styling |
| Express 5 | Backend API |
| PostgreSQL | Database |
| Drizzle ORM | Database access |
| Zod | Schema validation |
| TanStack Query | Server-state management |
| pnpm | Monorepo and package management |

## 🏗️ Project Structure

```text
quantlearn-new/
│
├── .agents/             # Agent-related project resources
├── api/
│   └── ai/              # AI-related API workspace
│
├── artifacts/           # Application workspaces
├── attached_assets/     # Project assets
├── lib/                 # Shared libraries
├── scripts/             # Development scripts
│
├── .gitignore
├── package.json
├── pnpm-lock.yaml
├── pnpm-workspace.yaml
├── quantum.md
├── tsconfig.json
├── tsconfig.base.json
└── vercel.json
```

## 🚀 Getting Started

Follow these instructions to set up the project locally.

### Prerequisites

Make sure you have installed:

- Node.js 24
- pnpm 10.15.0
- Git

### 1. Clone the repository

```bash
git clone https://github.com/parmeshwarvarfa-dot/quantlearn-new.git
```

### 2. Navigate to the project

```bash
cd quantlearn-new
```

### 3. Install dependencies

```bash
pnpm install
```

### 4. Configure environment variables

Create the required environment configuration for your local setup.

The API/database workspace requires:

```env
DATABASE_URL=your_postgresql_connection_string
```

Use the environment variables required by the relevant application workspaces and integrations. Never commit real API keys, passwords or database credentials.

### 5. Start the API server

```bash
pnpm --filter @workspace/api-server run dev
```

The documented API development port is `5000`.

## 🧪 Development Commands

### Type checking

```bash
pnpm run typecheck
```

### Build the project

```bash
pnpm run build
```

### Generate API hooks and validation schemas

```bash
pnpm --filter @workspace/api-spec run codegen
```

### Push database schema changes

For development environments only:

```bash
pnpm --filter @workspace/db run push
```

## 🌍 Deployment

The project has a deployed web application:

**[Open QuantumLearn](https://quantlearn-new.vercel.app/onboarding)**

The repository includes a `vercel.json` configuration file.

For deployment, configure the required environment variables and workspace build settings in your deployment environment.

## 🎓 Learning Vision

QuantumLearn aims to make quantum computing more accessible to students, developers and technology enthusiasts.

The broader vision is to build a learning environment where complex quantum concepts can become easier to understand and explore.

## 🔮 Future Direction

Potential areas for future development include:

- Structured quantum computing learning paths.
- Interactive quantum algorithm demonstrations.
- Quantum circuit visualization.
- Practical coding exercises.
- Progress tracking and learning milestones.
- AI-assisted learning support.
- Quantum computing project resources.

These are potential development directions, not claims about currently available functionality.

## 🤝 Contributing

Contributions, suggestions and ideas are welcome.

If you want to contribute:

1. Fork the repository.
2. Create a new feature branch.
3. Make your changes.
4. Test your implementation.
5. Submit a pull request describing your changes.

## 📄 License

This project declares the **MIT License** in its root `package.json`. See the repository's license file for the applicable license terms.

---

<div align="center">

### ⚛️ QuantumLearn

**Making Quantum Computing Easier to Explore.**

Built with curiosity, mathematics and technology.

[Live Platform](https://quantlearn-new.vercel.app/onboarding) · [GitHub Repository](https://github.com/parmeshwarvarfa-dot/quantlearn-new)

</div>
