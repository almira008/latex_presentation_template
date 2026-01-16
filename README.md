# LaTeX Beamer Presentation Template

Here is the beamer template I used for my weekly progress report on my Master's degree thesis. You can customize the color scheme by updating the RGB values in the colors.tex file and you can edit the elements in the customtheme.tex file as needed.

## Structure

```
├── presentation.tex       # Main presentation file
└── theme/
    ├── customtheme.tex   # Custom Beamer theme styling
    └── colors.tex        # Color scheme configuration
```

## Quick Start

1. Edit `presentation.tex` to add your content
2. Customize colors in `theme/colors.tex`
3. Compile with: `pdflatex presentation.tex`

## Customization

### Colors

Edit `theme/colors.tex` to customize the color scheme. The main colors are:

- **primary**: Main theme color (titles, structure)
- **secondary**: Accent color (bullet points)
- **tertiary**: Additional accent color
- **alertcolor**: For alert blocks
- **examplecolor**: For example blocks

You can use RGB values:
```latex
\definecolor{primary}{RGB}{0, 102, 204}
```


### Theme Elements

Edit `theme/customtheme.tex` to modify:

- Title page layout
- Frame title styling
- Footer content and layout
- Block styles
- Font sizes and styles
- Item bullet shapes

## Compilation

```bash
pdflatex presentation.tex
```

For bibliography or complex documents, run twice:
```bash
pdflatex presentation.tex
pdflatex presentation.tex
```
