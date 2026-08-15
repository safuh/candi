# C_and_I

**Software engineering across backend systems, AI, machine learning, quantitative systems, and modern web applications.**

url Live site https://candi-ochre.vercel.app/ · url Source repository https://github.com/safuh/candi

C_and_I is a personal engineering portfolio and technical workspace. It presents selected work, engineering capabilities, experiments, and technical notes across software engineering, artificial intelligence, machine learning, and quantitative systems.

The site is intentionally built as a lightweight Astro application rather than a template-heavy portfolio. The goal is to keep the implementation simple, fast, maintainable, and easy to evolve as the underlying work grows.

---

## Engineering Focus

### Backend Engineering

Python is the primary backend ecosystem, with a focus on designing maintainable APIs and service-oriented applications.

- FastAPI and asynchronous API development
- REST API architecture
- SQLAlchemy and relational data modeling
- PostgreSQL
- Alembic database migrations
- JWT authentication and authorization
- Pydantic-based validation
- Dependency injection and modular service architecture
- Configuration and environment management
- API integration and external services

### AI & LLM Engineering

Building applications that connect language models to data, APIs, documents, and executable tools.

- LLM integration
- Local model workflows with Ollama
- Retrieval-Augmented Generation (RAG)
- Embeddings and vector retrieval
- Structured model outputs
- Function and tool calling
- AI agents and orchestration
- Model-provider abstraction
- AI-powered backend services
- Privacy-oriented and local-first AI architectures

### Machine Learning

Exploring machine learning from data preparation and experimentation through model integration and application deployment.

- Python-based ML workflows
- NumPy and Pandas
- PyTorch
- TensorFlow / Keras
- Neural networks
- CNN and sequence-based models
- Time-series modeling
- Feature engineering
- Transfer learning and pretrained models
- Model evaluation and inference pipelines

### Quantitative Systems

Developing data-driven market and trading systems combining quantitative analysis, automation, technical modeling, and machine learning.

- Algorithmic strategy development
- TradingView and Pine Script
- Market-data ingestion
- WebSocket-based real-time data
- Technical analysis
- Market-structure analysis
- Backtesting and strategy evaluation
- Risk-management logic
- Position sizing
- ML model integration
- Python quantitative analysis

### Full-Stack Development

Building complete web applications across frontend, backend, database, and API layers.

- React
- JavaScript / TypeScript
- Redux
- HTML / CSS / Sass
- Tailwind CSS
- Bootstrap
- Figma-based interface implementation
- API integration
- Responsive web applications
- Low-code application development with Bubble

---

## Technology Stack

| Area | Technologies |
| --- | --- |
| **Primary language** | Python |
| **Backend** | FastAPI, SQLAlchemy, Pydantic, REST APIs |
| **Databases** | PostgreSQL, SQL |
| **Migrations** | Alembic |
| **Authentication** | JWT, access/refresh token architecture |
| **AI / LLM** | Ollama, LLM APIs, RAG, embeddings, tool calling |
| **Machine Learning** | PyTorch, TensorFlow, Keras, NumPy, Pandas |
| **Quantitative** | Pine Script, TradingView, CCXT, WebSockets |
| **Frontend** | Astro, React, TypeScript, JavaScript |
| **Styling** | CSS, Sass, Tailwind CSS, Bootstrap |
| **Design** | Figma |
| **Development** | Linux, Git, GitHub |

---

## About the Site

The portfolio is designed around a simple principle:

> **Show the engineering problem, the system behind the solution, and the technology used to implement it.**

Rather than treating the site as a list of frameworks, the structure separates **capabilities**, **technologies**, and eventually **proof through projects and technical work**.

The current visual direction uses a dark, technical interface with restrained blue accents, responsive layouts, and minimal UI chrome. The design is intended to feel closer to an engineering workspace than a generic corporate template.

---

## Project Structure

```text
candi/
├── public/
│   └── static assets
├── src/
│   ├── components/
│   │   ├── Nav.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── services.astro
│   │   └── blogs.astro
│   └── styles/
│       ├── global.css
│       ├── index.css
│       └── page-specific styles
├── package.json
└── README.md
```

Astro uses the `src/pages/` directory for routing. Components are kept in `src/components/`, shared document structure lives in `src/layouts/`, and styling is separated between global and page-level concerns.

---

## Local Development

### Requirements

- Node.js
- npm
- Git

### Clone the repository

```bash
git clone https://github.com/safuh/candi.git
cd candi
```

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

The Astro development server will normally be available at:

```text
http://localhost:4321
```

### Build for production

```bash
npm run build
```

The production build is generated in:

```text
./dist/
```

### Preview the production build

```bash
npm run preview
```

### Astro CLI

```bash
npm run astro -- --help
```

---

## Development Principles

The project is being developed around several engineering principles:

1. **Prefer clear architecture over unnecessary abstraction.**
2. **Keep components small and composable.**
3. **Treat accessibility and responsive behavior as first-class requirements.**
4. **Keep content separate from presentation where practical.**
5. **Use real projects as evidence of technical capability.**
6. **Avoid unnecessary dependencies.**
7. **Optimize for maintainability rather than visual complexity.**

---

## Roadmap

The portfolio is evolving from a basic personal site into a technical engineering portfolio.

- [x] Redesign homepage
- [x] Establish shared visual system
- [x] Improve navigation and document metadata
- [ ] Rebuild Services / Expertise around capabilities and proof
- [ ] Add structured Projects / Work section
- [ ] Rework technical blog / engineering notes
- [ ] Add professional About section
- [ ] Replace remaining legacy/template content
- [ ] Improve SEO and social metadata
- [ ] Accessibility audit
- [ ] Cross-device visual QA
- [ ] Production deployment and performance pass

---

## Status

**Active development.**

The site is a living portfolio: its content, projects, technical notes, and architecture will continue to evolve alongside the engineering work it represents.

---

## License

This repository contains a personal portfolio and its associated source code. Unless otherwise stated in a specific file or directory, the project should be treated as personal work rather than a general-purpose template or library.

---

## Contact

For professional enquiries, collaboration, or technical discussion, use the contact information provided on the portfolio site.
