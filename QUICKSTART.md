# Quick Start Guide for GitHub Pages Migration

## What You Have

I've created a one-page academic website inspired by classic web design principles. The site features:

- **Readable serif typography**: Georgia for comfortable long-form reading
- **Single-column layout**: Optimized 680px width for ideal line length
- **Italic emphasis**: Key terms highlighted (model theory, logic, fields, etc.)
- **Tree imagery**: Three images integrated as visual breaks between sections
- **Warm palette**: Off-white background (#fffef8) and dark text for readability
- **Simple interactions**: Links underline on hover
- **One-page design**: All content (about, papers, talks) scrolls smoothly

## Next Steps

### 1. Download Your Tree Images (IMPORTANT!)

Visit your current Squarespace site and download these images:

**For the header:**
- Right-click on the main tree image and save as `header-tree.jpg`

**For the gallery (the three images at the bottom):**
- Save them as `tree-1.jpg`, `tree-2.jpg`, and `tree-3.jpg`

Place all four images in the `images/` folder.

### 2. Add Your CV

Copy your CV PDF into the root folder and name it `cv.pdf`

### 3. Set Up GitHub Repository

```bash
# Create a new repository on GitHub named: yourusername.github.io
# Then in your terminal:

cd nramsey-site
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

### 4. Enable GitHub Pages

1. Go to your repository settings on GitHub
2. Navigate to "Pages" section
3. Select "main" branch as source
4. Save

Your site will be live at `https://yourusername.github.io` in a few minutes!

## Design Features

### Typography & Reading Experience
- Georgia serif font for comfortable reading
- 18px base font size
- 1.7 line height for optimal readability
- 680px maximum width (ideal line length)
- Generous spacing between paragraphs

### Visual Hierarchy
- Large, simple headers with Georgia
- Italic emphasis on key terms throughout
- Bullet points with custom styling (· instead of standard bullets)
- Images as section breaks

### Color Palette
- Warm off-white background (#fffef8)
- Dark, readable text (#2b2b2b)
- Classic blue links (#0066cc)
- Underline on hover for clear interaction

### Layout
- Single-column, centered design
- No sidebars or navigation
- Tree images placed strategically between sections
- "Return to top" link at bottom

## Customization Tips

### To update papers or talks:
Simply edit the HTML in `index.html` - the structure is straightforward.

### To change colors:
Edit `style.css` - search for color hex codes like `#2563eb`

### To adjust spacing:
Modify padding and margin values in `style.css`

## Why This Is Better Than Squarespace

1. **Free**: No hosting costs
2. **Fast**: Simple HTML/CSS loads instantly
3. **Portable**: All files are yours, no vendor lock-in
4. **Version controlled**: Track changes with Git
5. **Customizable**: Full control over every pixel
6. **Academic-appropriate**: Clean, distraction-free design

## Need Help?

See the detailed README.md file for more information, or check GitHub's documentation at https://docs.github.com/en/pages

---

The design emphasizes readability and timeless aesthetics - a site that feels substantial and academic without being stuffy or overly formal.
