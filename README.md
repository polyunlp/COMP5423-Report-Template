# COMP5423 Report Template
<div align="center">
<img src="figures/uw.png" alt="HKUDS%2FLightRAG | Trendshift" style="width: 333px; height: 100px;" width="333" height="100"/>
</div>


A LaTeX template for coursework reports in **COMP5423 - Natural Language Processing** at the Hong Kong Polytechnic University.

## Overview

This template provides a structured format for writing project.

## Project Structure

```
COMP5423-Report-Template/
├── COMP5423_reportTemplate.tex    # Main LaTeX document
├── notation.tex                    # Custom mathematical notation and commands
├── mybib.bib                       # Bibliography database
├── figures/                        # Directory for figures and images
│   ├── goose.png
│   ├── screenshot.png
│   ├── sign1.png
│   └── uw.png
└── settings_do_not_modify/         # Template settings (do not modify)
    ├── includes.tex                # Package includes and settings
    ├── titlepage.tex               # Title page template
    └── contributions.tex           # Contributions page template
```

## Getting Started

### Prerequisites

- A LaTeX distribution (e.g., TeX Live, MiKTeX, or MacTeX), or
- A LaTeX editor (e.g., Overleaf, TeXstudio, or VS Code with LaTeX extensions) [recommended!]

### Compilation

To compile the document, use one of the following methods:

#### With pdflatex
```bash
pdflatex COMP5423_reportTemplate.tex
bibtex COMP5423_reportTemplate
pdflatex COMP5423_reportTemplate.tex
pdflatex COMP5423_reportTemplate.tex
```

#### With Overleaf

1. Fork this repo:
![](./figures/screenshot-fork.png/)

2. Import COMP5423-Report-Template repo from Overleaf:
![](./figures/screenshot.png)

## License

This template is provided for educational purposes for COMP5423 students at the Hong Kong Polytechnic University.

