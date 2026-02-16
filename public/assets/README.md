# Assets Folder

This folder contains all static assets for the ModernCore Web Design website.

## Folder Structure

- **images/logo/** - Company logo files (PNG, SVG recommended)
- **images/hero/** - Hero section background images and graphics
- **images/projects/** - Project portfolio images and screenshots
- **images/team/** - Team member photos

## How to Use Images

### Adding Images
1. Place your images in the appropriate subfolder
2. Use descriptive filenames (e.g., `logo-white.png`, `project-ecommerce.jpg`)

### Referencing Images in Code
Images in the public folder can be referenced directly from the root:

```astro
<!-- Example: Logo -->
<img src="/assets/images/logo/logo.png" alt="ModernCore Logo" />

<!-- Example: Project Image -->
<img src="/assets/images/projects/ecommerce-site.jpg" alt="E-commerce Project" />

<!-- Example: Hero Background -->
<div style="background-image: url('/assets/images/hero/background.jpg')"></div>
```

### Image Optimization Tips
- Use WebP or AVIF format for better compression
- Optimize images before uploading (use tools like TinyPNG, Squoosh)
- Recommended sizes:
  - Logo: 200-400px width
  - Hero images: 1920px width
  - Project thumbnails: 800px width
  - Team photos: 400-600px width

## Supported Formats
- PNG (for logos with transparency)
- JPG/JPEG (for photos)
- SVG (for scalable graphics and logos)
- WebP (for optimized web images)
- GIF (for simple animations)
