# .github.io
my personal website

## Current Status

✅ Folder structure is now organized
✅ Image references are properly configured  
✅ Ready to add images to the `img/` folder

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

To add images to your repository:
1. Copy your image files into the `img/` folder
2. Stage and commit them: `git add img/your-image.jpg`
3. Push to GitHub: `git push`

### Source Files
- Keep `.qmd` (Quarto markdown) files in the root directory
- The `_quarto.yml` file configures the website structure
- Custom styling goes in `styles.css`

### Generated Files
- Quarto generates HTML files and places them in the `docs/` folder (configured in `_quarto.yml`)
- The `docs/` folder is used for GitHub Pages deployment

