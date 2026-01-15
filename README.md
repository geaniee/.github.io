# .github.io
my personal website

## Folder Structure

```
/
├── img/                    # Images folder
│   ├── project.jpg        # Favicon for the website
│   ├── nav.jpg           # Logo for the navbar
│   └── wine.jpg          # Data visualization image
├── docs/                  # Generated output (created by Quarto)
├── *.qmd                 # Quarto source files
├── *.html                # Generated HTML files
├── _quarto.yml           # Quarto configuration
├── styles.css            # Custom CSS styling
└── README.md             # This file
```

## How to Organize Files

### Images
Place all image files in the `img/` folder. Reference them in your Quarto documents using:
```markdown
![Alt text](img/your-image.jpg)
```

### Source Files
- Keep `.qmd` (Quarto markdown) files in the root directory
- The `_quarto.yml` file configures the website structure
- Custom styling goes in `styles.css`

### Generated Files
- Quarto generates HTML files and places them in the `docs/` folder (configured in `_quarto.yml`)
- The `docs/` folder is used for GitHub Pages deployment

