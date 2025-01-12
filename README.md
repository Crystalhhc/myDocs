# Demo site of MKdocs for Multi-language
This is a demo site for Multi-language with MKdocs Material theme. You can check out  my post [Build a Multi-language Website with MKdocs Material Theme](https://crystalhhc.github.io/my-sharing/blog/2025/01/11/build-multi-language-website-mkdocs-material.html) for details.

## Project Layout

```
myDocs/
├── .venv/                 # Virtual environment directory
├── mydocs-en/             # English documentation project
│   ├── docs/
│   │   ├── index.md       # The documentation homepage (English)
│   │   ├── blog/
│   │   │   ├── posts/
│   │   │   └── index.md
│   │   └── ...            # Other markdown pages, images and other files
│   └── mkdocs.yml         # The configuration file for English docs
├── mydocs-zh-TW/          # Traditional Chinese documentation project
│   ├── docs/
│   │   ├── index.md       # The documentation homepage (Traditional Chinese)
│   │   ├── blog/
│   │   │   ├── posts/
│   │   │   └── index.md
│   │   └── ...            # Other markdown pages, images and other files
│   └── mkdocs.yml         # The configuration file for Traditional Chinese docs
└── README.md              # This file, containing project overview and instructions
```
