# WooCommerce Category Block - Display Categories in Grid & Slider Layout

[![WordPress](https://img.shields.io/badge/WordPress-6.0%2B-blue.svg)](https://wordpress.org/)
[![WooCommerce](https://img.shields.io/badge/WooCommerce-6.0%2B-purple.svg)](https://woocommerce.com/)
[![License](https://img.shields.io/badge/License-GPL--2.0-green.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/jenishwpsd-afk/wc-category-block.svg)](https://github.com/jenishwpsd-afk/wc-category-block/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/jenishwpsd-afk/wc-category-block.svg)](https://github.com/jenishwpsd-afk/wc-category-block/issues)

> 🚀 **Display WooCommerce product categories beautifully** with this powerful Gutenberg block plugin. Features **category filter**, **grid layout**, **slider carousel**, and **responsive design**. Perfect for WooCommerce stores that want to improve product discovery and showcase categories professionally.

**🔍 Keywords:** `woocommerce category block` • `woocommerce category filter` • `woocommerce category grid` • `woocommerce category slider` • `gutenberg woocommerce` • `product category display` • `category carousel` • `woocommerce block plugin`

---

## 📸 Screenshots

### WooCommerce Category Grid Layout
![WooCommerce Category Grid](https://github.com/user-attachments/assets/16dccdfd-5e87-4e56-ba67-506e308d86ae)

### WooCommerce Category Slider Layout
![WooCommerce Category Slider](https://github.com/user-attachments/assets/14ff08eb-9d21-471d-893c-9186e9acc449)

---

## ⭐ Why Choose WooCommerce Category Block?

This **WooCommerce category block plugin** is the perfect solution for displaying product categories in your online store:

✅ **WooCommerce Category Filter** - Filter and display specific categories  
✅ **WooCommerce Category Grid** - Beautiful responsive grid layout  
✅ **WooCommerce Category Slider** - Modern carousel with navigation  
✅ **Gutenberg Block** - Native WordPress block editor integration  
✅ **Fully Responsive** - Perfect on mobile, tablet, and desktop  
✅ **Product Category Display** - Show product counts, images, and names  
✅ **Easy Customization** - No coding required  
✅ **Fast & Lightweight** - Optimized performance  
✅ **SEO Friendly** - Clean semantic HTML markup  
✅ **Free & Open Source** - GPL licensed  

---

## 🎯 Features

### 🎨 Display Options
- **Grid Layout** - Responsive category grid with 1-6 columns
- **Slider Layout** - Touch-enabled carousel with navigation arrows
- **Category Filter** - Show all or limit to specific categories
- **Product Count** - Display number of products per category
- **Empty Categories** - Show/hide categories with no products

### ⚙️ Customization Settings
- **Columns Control** - Choose 1-6 columns for any layout
- **Category Limit** - Display specific number of categories (1-50)
- **Sort Options** - Sort by name, count, ID, or slug
- **Order Direction** - Ascending or descending order
- **Responsive Breakpoints** - Automatic mobile/tablet optimization

### 🛠️ Technical Features
- Native Gutenberg block integration
- WooCommerce REST API compatible
- Translation ready (i18n)
- RTL language support
- No jQuery dependency
- Lazy loading images
- Clean & semantic code

---

## 📦 Installation

### Method 1: WordPress Admin (Recommended)

1. Download the [latest release](https://github.com/jenishwpsd-afk/wc-category-block/releases)
2. Go to WordPress Admin → Plugins → Add New → Upload Plugin
3. Upload the ZIP file and click "Install Now"
4. Activate the plugin
5. Done! Start using the WooCommerce category block

### Method 2: Manual Installation

```bash
# Navigate to WordPress plugins directory
cd wp-content/plugins/

# Clone the repository
git clone https://github.com/jenishwpsd-afk/wc-category-block.git

# Navigate to plugin folder
cd wc-category-block

# Install dependencies
npm install

# Build the plugin
npm run build
```

### Method 3: Development Setup

**Using NPM:**
```bash
# Clone repository
git clone https://github.com/jenishwpsd-afk/wc-category-block.git
cd wc-category-block

# Install dependencies
npm install

# Start development server (auto-reload)
npm start

# Build for production
npm run build
```

**Using Yarn:**
```bash
# Clone repository
git clone https://github.com/jenishwpsd-afk/wc-category-block.git
cd wc-category-block

# Install dependencies
yarn install

# Start development server
yarn start

# Build for production
yarn build
```

---

## 🚀 Quick Start Guide

### Step 1: Add the Block

1. Open WordPress page/post editor
2. Click the `+` button to add a block
3. Search for **"WC Category"** or **"WooCommerce Category"**
4. Click to insert the block

**Quick Insert:** Type `/wc category` and press Enter

### Step 2: Configure Settings

In the **Block Settings Panel** (right sidebar):

**Layout Settings:**
- **Display Layout**: Choose Grid or Slider
- **Columns**: Select 1-6 columns

**Category Settings:**
- **Show All Categories**: Toggle to display all
- **Number of Categories**: Limit display (1-50)
- **Order By**: Name, Count, ID, or Slug
- **Order**: Ascending or Descending
- **Show Product Count**: Display product numbers
- **Hide Empty Categories**: Hide categories with 0 products

### Step 3: Publish

Click "Update" or "Publish" and view your page!

---

## 🎨 Customization

### CSS Customization

Add custom CSS to your theme to style the categories:

```css
/* Customize category cards */
.wc-category-block .wc-cat-item {
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
}

/* Hover effect */
.wc-category-block .wc-cat-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 4px 16px rgba(0,0,0,0.15);
}

/* Category title */
.wc-category-block .wc-cat-title {
    font-size: 18px;
    font-weight: 600;
    color: #333;
}

/* Product count */
.wc-category-block .wc-cat-count {
    font-size: 14px;
    color: #666;
}

/* Grid spacing */
.wc-cat-grid .wc-cat-grid-container {
    gap: 30px;
}

/* Slider navigation arrows */
.wc-cat-slider .swiper-button-next,
.wc-cat-slider .swiper-button-prev {
    color: #ff6b6b;
}
```

### Available CSS Classes

```css
.wc-category-block        /* Main container */
.wc-cat-grid             /* Grid layout */
.wc-cat-slider           /* Slider layout */
.wc-cat-cols-3           /* Column count (1-6) */
.wc-cat-item             /* Individual category */
.wc-cat-image            /* Category image */
.wc-cat-content          /* Text content */
.wc-cat-title            /* Category name */
.wc-cat-count            /* Product count */
```

---

## 💻 Development

### Requirements

- Node.js 14+ and npm/yarn
- WordPress 6.0+
- WooCommerce 6.0+
- PHP 7.4+

### Development Commands

```bash
# Install dependencies
npm install

# Development mode (hot reload)
npm start

# Build for production
npm run build

# Lint JavaScript
npm run lint:js

# Format code
npm run format

# Update packages
npm run packages-update
```

### Project Structure

```
wc-category-block/
├── assets/              # Frontend assets
│   ├── frontend.js     # Slider initialization
│   └── style.css       # Additional styles
├── build/              # Compiled files (auto-generated)
├── src/                # Source files
│   ├── block.json      # Block configuration
│   ├── index.js        # Block registration
│   ├── edit.js         # Editor component
│   ├── render.php      # Frontend rendering
│   ├── editor.scss     # Editor styles
│   └── style.scss      # Frontend styles
├── screenshots/        # Plugin screenshots
├── package.json        # Dependencies
└── wc-category-block.php  # Main plugin file
```

---

## 🐛 Troubleshooting

### Block Not Appearing?
```bash
npm run build
# Then clear WordPress cache
```

### Categories Not Showing?
1. Verify WooCommerce is active
2. Check if categories exist in WooCommerce → Products → Categories
3. Disable "Hide Empty Categories" option
4. Check category limit isn't too low

### Slider Not Working?
1. Check browser console for JavaScript errors
2. Clear browser cache (Ctrl+Shift+R)
3. Verify Swiper.js is loading (view page source)
4. Disable conflicting plugins

### Styling Issues?
1. Clear all caches (WordPress + browser)
2. Verify build folder has CSS files
3. Check theme CSS conflicts
4. Inspect with browser DevTools

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

**Coding Standards:**
- Follow [WordPress Coding Standards](https://developer.wordpress.org/coding-standards/)
- Test on multiple browsers
- Update documentation

---

## 📊 SEO Keywords

This plugin is optimized for:
- woocommerce category block
- woocommerce category filter
- woocommerce category grid
- woocommerce category slider
- woocommerce category display
- gutenberg woocommerce categories
- product category block
- woocommerce category carousel
- wordpress category block
- woocommerce block plugin
- category filter gutenberg
- woocommerce product categories
- wordpress woocommerce block
- category grid wordpress
- category slider woocommerce

---

## 🌟 Show Your Support

If this plugin helped your WooCommerce store:

⭐ Star this repository  
🐦 [Tweet about it](https://twitter.com/intent/tweet?text=Check%20out%20this%20awesome%20WooCommerce%20Category%20Block%20plugin!&url=https://github.com/jenishwpsd-afk/wc-category-block)  
📝 Write a review  
🍴 Fork and contribute  

---

## 📄 License

This project is licensed under the GPL-2.0 License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Jenish Dholakiya**
- GitHub: [@jenishwpsd-afk](https://github.com/jenishwpsd-afk)
- Repository: [wc-category-block](https://github.com/jenishwpsd-afk/wc-category-block)

---

## 📞 Support

- 🐛 [Report Bug](https://github.com/jenishwpsd-afk/wc-category-block/issues)
- 💡 [Request Feature](https://github.com/jenishwpsd-afk/wc-category-block/issues)
- 💬 [Discussions](https://github.com/jenishwpsd-afk/wc-category-block/discussions)
- ⭐ [Star on GitHub](https://github.com/jenishwpsd-afk/wc-category-block)

---

## 🔗 Related Projects

Looking for more WooCommerce blocks?
- [WooCommerce Product Block](https://github.com/woocommerce/woocommerce-blocks)
- [WooCommerce Filter Blocks](https://github.com/woocommerce/woocommerce-blocks)

---

## 📈 Stats

![GitHub stars](https://img.shields.io/github/stars/jenishwpsd-afk/wc-category-block?style=social)
![GitHub forks](https://img.shields.io/github/forks/jenishwpsd-afk/wc-category-block?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/jenishwpsd-afk/wc-category-block?style=social)
![GitHub issues](https://img.shields.io/github/issues/jenishwpsd-afk/wc-category-block)
![GitHub pull requests](https://img.shields.io/github/issues-pr/jenishwpsd-afk/wc-category-block)
![GitHub last commit](https://img.shields.io/github/last-commit/jenishwpsd-afk/wc-category-block)

---

<div align="center">

**Made with ❤️ for the WooCommerce Community**

[⬆ Back to Top](#woocommerce-category-block---display-categories-in-grid--slider-layout)

</div>
