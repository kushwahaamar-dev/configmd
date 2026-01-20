# 🛠️ Skills Collection

A comprehensive collection of AI-powered skills for extending Claude's capabilities across various domains including document processing, frontend development, design, automation, and more.

---

## 🎯 What Are Skills?

Skills are specialized instruction sets that extend Claude's capabilities for specific tasks. Each skill contains:

- **SKILL.md** - Core instructions with YAML frontmatter defining name, description, and detailed guidance
- **scripts/** - Executable utilities and helper scripts
- **examples/** - Reference implementations and usage patterns
- **resources/** - Templates, assets, and additional files

---

## 📚 Skills Catalog

### 🎨 Design & Creative

| Skill | Description | Key Features |
|-------|-------------|--------------|
| **[algorithmic-art](./algorithmic-art)** | Generative art using p5.js | Seeded randomness, interactive parameters, flow fields, particle systems |
| **[canvas-design](./canvas-design)** | Visual art creation | PNG/PDF output, design philosophy, posters, static art pieces |
| **[frontend-design](./frontend-design)** | Production-grade frontend interfaces | High design quality, distinctive UI, avoids generic AI aesthetics |
| **[theme-factory](./theme-factory)** | Styling artifacts with themes | 10 pre-set themes, custom theme generation, slides/docs/HTML |
| **[brand-guidelines](./brand-guidelines)** | Anthropic brand application | Official colors, typography, visual formatting |

### 📄 Document Processing

| Skill | Description | Key Features |
|-------|-------------|--------------|
| **[docx](./docx)** | Word document manipulation | Create, edit, tracked changes, comments, formatting preservation |
| **[pdf](./pdf)** | PDF toolkit | Text/table extraction, form filling, merge/split, creation |
| **[pptx](./pptx)** | PowerPoint presentations | Create, edit, layouts, speaker notes, comments |
| **[xlsx](./xlsx)** | Spreadsheet operations | Formulas, formatting, data analysis, visualization |

### 🌐 Web Development

| Skill | Description | Key Features |
|-------|-------------|--------------|
| **[shadcn-ui-designing](./shadcn-ui-designing)** | Shadcn UI components | Minimalism, accessibility, beautiful defaults |
| **[web-artifacts-builder](./web-artifacts-builder)** | Complex web artifacts | React, Tailwind, shadcn/ui, state management, routing |
| **[vercel-react-best-practices](./vercel-react-best-practices)** | React/Next.js optimization | Performance patterns, bundle optimization, data fetching |
| **[web-design-guidelines](./web-design-guidelines)** | UI code review | Accessibility audits, design compliance, UX review |
| **[webapp-testing](./webapp-testing)** | Web app testing | Playwright automation, screenshots, browser logs |

### 🔧 Development Tools

| Skill | Description | Key Features |
|-------|-------------|--------------|
| **[mcp-builder](./mcp-builder)** | MCP server creation | Python FastMCP, Node/TypeScript SDK, API integration |
| **[ml-pipeline-workflow](./ml-pipeline-workflow)** | MLOps pipelines | Training, validation, deployment, end-to-end automation |
| **[skill-creator](./skill-creator)** | Create new skills | Templates, validation, packaging |

### 📝 Content & Communication

| Skill | Description | Key Features |
|-------|-------------|--------------|
| **[doc-coauthoring](./doc-coauthoring)** | Documentation workflow | Proposals, technical specs, decision docs, iteration |
| **[internal-comms](./internal-comms)** | Internal communications | Status reports, newsletters, FAQs, incident reports |
| **[slack-gif-creator](./slack-gif-creator)** | Slack-optimized GIFs | Animation concepts, validation, constraints |

---

## 🚀 Quick Start

### Using a Skill

1. Navigate to the skill directory
2. Read the `SKILL.md` file for instructions
3. Use any provided scripts in `scripts/`
4. Reference examples in `examples/` if available

### Example: Using the PDF Skill

```bash
# Extract text from a PDF
python pdf/scripts/extract_text.py document.pdf

# Fill a PDF form
python pdf/scripts/fill_form.py template.pdf data.json output.pdf
```

### Example: Using the PPTX Skill

```bash
# Create presentation from HTML
node pptx/scripts/html2pptx.js input.html output.pptx

# Generate thumbnail
python pptx/scripts/thumbnail.py presentation.pptx
```

---

## 📁 Repository Structure

```
skills/
├── algorithmic-art/
│   ├── SKILL.md
│   └── examples/
├── docx/
│   ├── SKILL.md
│   ├── ooxml/          # XML schemas
│   └── scripts/        # Document utilities
├── pdf/
│   ├── SKILL.md
│   └── scripts/        # PDF manipulation tools
├── pptx/
│   ├── SKILL.md
│   ├── ooxml/          # PowerPoint schemas
│   └── scripts/        # Presentation tools
├── theme-factory/
│   ├── SKILL.md
│   └── themes/         # Pre-built theme definitions
├── vercel-react-best-practices/
│   ├── SKILL.md
│   └── rules/          # Performance optimization rules
└── ...
```

---

## 🤝 Contributing

Want to add a new skill? Use the `skill-creator` skill:

1. Read `skill-creator/SKILL.md` for guidelines
2. Run `python skill-creator/scripts/init_skill.py my-new-skill`
3. Add your instructions to `SKILL.md`
4. Validate with `python skill-creator/scripts/quick_validate.py`
5. Submit a pull request

---

## 📄 License

See individual skill folders for specific licensing information. Most skills include a `LICENSE.txt` file.

---

## 🔗 Links

- **Repository**: [github.com/kushwahaamar-dev/configmd](https://github.com/kushwahaamar-dev/configmd)
- **Author**: [@kushwahaamar-dev](https://github.com/kushwahaamar-dev)

---

*Built with ❤️ for extending AI capabilities*
