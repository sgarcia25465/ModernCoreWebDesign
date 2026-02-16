# Logo Guide for ModernCore Web Design

## Current Logo Files

Your website currently uses placeholder logo files. Replace them with your actual logo designs:

### 1. **logo-full.svg** (Full Logo)
- **Location:** `public/assets/images/logo/logo-full.svg`
- **Usage:** Displayed in the navigation header on desktop
- **Recommended specs:**
  - Format: SVG, PNG, or WebP
  - Dimensions: 180px wide x 40-50px tall
  - Should include your full company name/wordmark
  - Background: Transparent

### 2. **logo-icon.svg** (Icon/Mark Logo)
- **Location:** `public/assets/images/logo/logo-icon.svg`
- **Usage:** Displayed in the navigation header on mobile devices
- **Recommended specs:**
  - Format: SVG, PNG, or WebP
  - Dimensions: 40px x 40px (square)
  - Should be a simple icon or monogram (like just "M" for ModernCore)
  - Background: Transparent

## How to Replace Placeholder Logos

1. **Save your logo files** with these exact names:
   - `logo-full.svg` (or `.png`)
   - `logo-icon.svg` (or `.png`)

2. **Copy to the logo folder:**
   ```
   /Users/kevingallor/Web Folder /Test Website /public/assets/images/logo/
   ```

3. **If using PNG instead of SVG**, update the file paths in:
   - File: `src/layouts/Layout.astro`
   - Lines: ~21-22
   - Change `.svg` to `.png`

## Tips for Best Results

- **Use SVG format when possible** - scales perfectly at any size
- **Ensure transparent backgrounds** - so logo works on any color
- **Test on mobile** - make sure the icon logo is recognizable when small
- **Keep it simple** - complex logos may not display well at header size

## Need Help Creating Logos?

If you need to create logos:
- **Canva** (canva.com) - Easy online design tool
- **Figma** (figma.com) - Professional design tool
- **Adobe Illustrator** - Professional vector graphics
- **LogoMakr** (logomakr.com) - Quick logo creation
