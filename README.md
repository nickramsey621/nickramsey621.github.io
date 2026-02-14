# Nicholas Ramsey - Academic Website

A clean, readable one-page academic website for hosting on GitHub Pages.

## Design Philosophy

This site takes inspiration from classic web design: readable serif typography, generous line spacing, and content-first presentation. The design features:

- **Serif typography** (Georgia) for better reading on screens
- **Single column layout** optimized for reading at 680px width
- **Italic emphasis** on key terms (model theory, logic, algebra, etc.)
- **Tree imagery** integrated throughout as visual breaks
- **Warm background** (#fffef8) that's easy on the eyes
- **Simple, underlined hover effects** on links

## Setup Instructions

### 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `username.github.io` (replace `username` with your GitHub username)
   - For example: `nramsey.github.io`
3. Make it public
4. Don't initialize with README (we already have one)

### 2. Download Images from Your Current Site

You'll need to download these tree images from your Squarespace site:

1. **Header image**: Go to your current site, right-click on the header tree image, and save it as `images/header-tree.jpg`
2. **Three gallery images**: Save the three tree images at the bottom of your site as:
   - `images/tree-1.jpg`
   - `images/tree-2.jpg`
   - `images/tree-3.jpg`

The images you need are at these locations on your Squarespace site:
- `https://images.squarespace-cdn.com/content/v1/5fc1ac74239b07229136bd59/1606528554131-FVEKNWLWDXAL7MXZF23O/illustration-1.jpg`
- `https://images.squarespace-cdn.com/content/v1/5fc1ac74239b07229136bd59/1606528587663-KHLAZVC1PXTN1QDJQKX4/3447_001.jpg`
- `https://images.squarespace-cdn.com/content/v1/5fc1ac74239b07229136bd59/1606528640873-I23CVJF7PU72WQGZ8PUY/3447_004.jpg`

### 3. Add Your CV

Place your CV PDF file in the root directory and name it `cv.pdf`

You can also create a `slides` folder for any presentation slides referenced in the talks section.

### 4. Upload to GitHub

#### Option A: Using Git Command Line

```bash
# Navigate to your website folder
cd nramsey-site

# Initialize git repository
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit - academic website"

# Add your GitHub repository as remote
git remote add origin https://github.com/username/username.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

#### Option B: Using GitHub Desktop or Web Interface

1. Download [GitHub Desktop](https://desktop.github.com/)
2. Create a new repository from your local folder
3. Publish to GitHub

### 5. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings"
3. Click "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Your site will be live at `https://username.github.io`

## File Structure

```
nramsey-site/
├── index.html          # Main website file
├── style.css           # Styles
├── cv.pdf             # Your curriculum vitae
├── README.md          # This file
├── images/            # Image folder
│   ├── header-tree.jpg
│   ├── tree-1.jpg
│   ├── tree-2.jpg
│   └── tree-3.jpg
└── slides/            # Optional: presentation slides
    ├── Cetraro.pdf
    └── Mathematics-of-Truth.pdf
```

## Customization

### Updating Content

Simply edit `index.html` to update your papers, talks, or contact information.

### Changing Colors

Edit `style.css` to customize:
- Link color: Search for `#0066cc`
- Background: Search for `#fffef8` (warm off-white)
- Text colors: Search for `#2b2b2b` and `#1a1a1a`

### Changing Typography

The site uses Georgia (serif) for a classic academic feel. To change:
- Find `font-family: Georgia` in `style.css`
- Replace with your preferred font

### Adjusting Layout

The site is fully responsive and works on all devices. To adjust spacing or sizing, modify the values in `style.css`.

## Features

- 📖 Readable serif typography (Georgia)
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Classic, timeless design
- 🌲 Tree imagery as visual breaks
- 🔗 Easy-to-update content
- ⚡ Fast loading, no dependencies
- 🆓 Free hosting on GitHub Pages
- ✨ Warm, inviting color palette

## Updating Your Site

To make changes:

1. Edit the files locally
2. Commit and push to GitHub:
   ```bash
   git add .
   git commit -m "Update research papers"
   git push
   ```
3. Changes will appear on your site within a few minutes

## Domain Setup (Optional)

If you want to use a custom domain like `nramseymath.com`:

1. In your repository settings, add your custom domain under "Pages"
2. Update your domain's DNS settings to point to GitHub Pages
3. See [GitHub's custom domain documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

## Support

For GitHub Pages issues, see the [official documentation](https://docs.github.com/en/pages).

---

**Current Design Notes:**

- One-page scrolling design
- Research and talks integrated into single page
- Maintains tree imagery aesthetic from original site
- Clean, academic look with excellent readability
- All content easily accessible without navigation
