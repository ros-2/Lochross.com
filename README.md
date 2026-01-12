# Lochross - Automation Consulting Website

Professional website for Philip Ross, an automation consultant based in Dundee, Scotland, helping organizations automate repetitive tasks and improve efficiency.

**Live Site:** [https://ros-2.github.io/](https://ros-2.github.io/)

## Project Overview

This is a static website built with vanilla HTML, CSS, and JavaScript, hosted on GitHub Pages. The site showcases automation consulting services, completed projects, and provides contact information for potential clients.

### Key Features

- **Portfolio showcase** with 7 completed automation projects demonstrating 14× ROI
- **Responsive design** optimized for mobile and desktop
- **Fast loading times** with optimized assets and minimal dependencies
- **Professional branding** with navy blue and orange color scheme
- **Contact form** integration with Formspree
- **Mobile-friendly navigation** with hamburger menu

## Project Structure

```
/
├── assets/
│   └── icons/          # Favicon and app icons (various sizes)
├── css/
│   └── styles.css      # Main stylesheet with responsive design
├── docs/
│   ├── about.txt       # Project documentation
│   ├── llms.txt        # LLM optimization content
│   └── google-analytics-tag.html  # Analytics setup reference
├── js/
│   ├── contact-form.js # Form submission handling
│   └── navigation.js   # Mobile navigation functionality
├── pages/
│   ├── about.html      # About page
│   ├── case-studies.html  # Case studies (coming soon)
│   ├── contact.html    # Contact page with form
│   ├── faq.html        # FAQ page
│   ├── process.html    # Process explanation
│   ├── projects.html   # Portfolio of completed projects
│   ├── services.html   # Services offered
│   └── testimonials.html  # Client testimonials
│
├── index.html          # Homepage
├── robots.txt          # Search engine crawler instructions
├── sitemap.xml         # Site structure for search engines
├── site.webmanifest    # PWA manifest for app-like experience
├── CNAME               # Custom domain configuration
└── googlea7057464435666a5.html  # Google Search Console verification
```

## Optimizations

### SEO (Search Engine Optimization)

The site is heavily optimized for search engines to ensure high visibility:

- **Meta Tags:** Comprehensive meta tags including title, description, keywords, and author
- **Open Graph Tags:** Social media sharing optimization for Facebook, LinkedIn, etc.
- **Twitter Cards:** Optimized previews when shared on Twitter
- **Structured Data (Schema.org):**
  - `ProfessionalService` schema for business information
  - `FAQPage` schema for common questions
  - Helps search engines understand the content and display rich snippets
- **Semantic HTML:** Proper use of heading hierarchy and semantic elements
- **Canonical URLs:** Prevents duplicate content issues
- **Hreflang Tags:** Indicates language/region targeting (en-GB)
- **Sitemap.xml:** Complete site structure for efficient crawling
- **Robots.txt:** Crawler directives and sitemap location
- **Fast Loading:** Minimal dependencies and optimized assets improve rankings
- **Mobile Responsive:** Mobile-friendly design is a ranking factor
- **Internal Linking:** Strategic linking between related pages

### LLM Optimization (AI Assistant Optimization)

The site is optimized for AI assistants like ChatGPT, Claude, and Perplexity:

- **llms.txt file:** Located in `/docs/llms.txt`, provides structured information for LLMs to understand:
  - What the business does
  - Services offered
  - Project results and ROI
  - Geographic service area
  - Contact information
- **Structured Data:** Schema.org markup helps LLMs extract accurate information
- **FAQ Schema:** Enables LLMs to provide accurate answers to common questions
- **Clear Content Hierarchy:** Well-organized content makes it easy for LLMs to parse
- **Semantic HTML:** Proper markup helps LLMs understand content relationships

This optimization ensures that when users ask AI assistants about automation consulting in Scotland or Philip Ross, the assistants can provide accurate, up-to-date information.

### Performance Optimizations

- **Font Loading:** Preconnect to Google Fonts and async loading with fallbacks
- **Minimal JavaScript:** Only essential scripts, loaded at appropriate times
- **CSS-Only Features:** Tabs and navigation use CSS instead of JavaScript where possible
- **Optimized Images:** Proper icon sizes for different devices
- **Cache Control:** HTTP cache headers for static assets
- **No Framework Overhead:** Vanilla HTML/CSS/JS keeps the site lightweight

### Analytics & Tracking

- **Google Analytics 4:** Tracks visitor behavior and site performance
- **Google Search Console:** Monitors search performance and indexing
- **Form Submissions:** Tracked through Formspree integration

## Technology Stack

- **HTML5:** Semantic markup with accessibility considerations
- **CSS3:** Custom properties (CSS variables), Flexbox, Grid
- **JavaScript (ES6+):** Minimal vanilla JavaScript for interactivity
- **Google Fonts:** Montserrat (headings) and Open Sans (body text)
- **Formspree:** Contact form backend
- **GitHub Pages:** Free, reliable hosting with HTTPS

## Development

### Local Development

To run locally, simply open `index.html` in a web browser. For a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

### Making Changes

1. Edit HTML files in root (index.html) or `/pages/` directory
2. Update styles in `/css/styles.css`
3. Modify scripts in `/js/` directory
4. Test locally before committing
5. Commit and push to main branch - GitHub Pages will auto-deploy

### Important Notes

**Do not move these files from root:**
- `index.html` - GitHub Pages requires this in root
- `robots.txt` - Must be at domain root for crawlers
- `sitemap.xml` - Expected at domain root by search engines
- `CNAME` - Required in root for custom domain
- `googlea7057464435666a5.html` - Google verification must be at root
- `site.webmanifest` - Referenced from HTML at root path

## Contact

For inquiries about the website or automation consulting services:
- **Email:** philip@lochross.com
- **Website:** [https://ros-2.github.io/](https://ros-2.github.io/)
- **Location:** Dundee, Scotland

## License

© 2024 Philip Ross / Lochross. All rights reserved.
