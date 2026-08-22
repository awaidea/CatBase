# Knowledge Base

A comprehensive learning knowledge base covering knowledge point organization across multiple academic disciplines.

## Project Introduction

This project aims to provide learners with systematic discipline knowledge organization, written in Markdown format for easy reading, editing, and version control. All content can be viewed in any Markdown editor or through an MkDocs documentation website.

## Project Structure

```
knowledge-base/
├── docs/
│   ├── source/
│   │   └── css/           # Style files
│   │       ├── font.css
│   │       └── glass.css
│   ├── images/            # Image resources
│   │   ├── avatar.png
│   │   └── wallpaper.jpeg
│   ├── Content/           # Knowledge content
│   │   ├── biology/       # Biology
│   │   ├── chemistry/     # Chemistry
│   │   ├── chinese/       # Chinese
│   │   ├── english/       # English
│   │   ├── history/       # History
│   │   ├── math/          # Math
│   │   ├── physics/       # Physics
│   │   ├── politics/      # Politics
│   │   └── index.md       # Quick Index
│   └── index.md           # Project Home
└── mkdocs.yml             # MkDocs Config File
```

## Subject Categories

The knowledge base currently contains the following subject contents:

- **Biology** - Life science related knowledge points
- **Chemistry** - Chemical principles and experiments
- **Chinese** - Chinese language and literature
- **English** - English language learning
- **History** - World history and Chinese history
- **Math** - Mathematical formulas and problem-solving methods
- **Physics** - Physical principles and laws
- **Politics** - Political theory and current affairs

## Quick Start

### Local Browsing

1. Clone the project locally:
```bash
git clone https://gitee.com/awaidea/knowledge-base.git
cd knowledge-base
```

2. Preview locally using MkDocs (MkDocs installation required):
```bash
mkdocs serve
```

3. Open `http://localhost:8000` in your browser to view the documentation website.

### Direct Reading

View the `docs/Content/index.md` file directly for a quick index, or browse the Markdown files under each subject directory.

## Tech Stack

- **Document Format**: Markdown
- **Documentation Generation**: MkDocs
- **Style**: Custom CSS Theme

## Contributing

Welcome learners and educators to contribute knowledge content:

1. Fork this project
2. Create your branch (`git checkout -b feature/new-content`)
3. Commit your changes (`git commit -am 'Add new knowledge points'`)
4. Push to the branch (`git push origin feature/new-content`)
5. Create a Pull Request

## License

This project is open sourced under the license specified in the [LICENSE](LICENSE) file.

## Contact Info

- Project Address: https://gitee.com/awaidea/knowledge-base
- Issue Feedback: Please submit in Gitee Issues

---

*Knowledge changes destiny, learning creates the future.*