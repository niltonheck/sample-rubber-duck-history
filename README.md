# Rubber Duck Invasion - Web Scraping Test Site

This repository contains a simple static website designed specifically for testing web scraping techniques. It presents a fictional story about a rubber duck invasion in Bergamo, Italy, with various pages and content structures that make it ideal for practicing different scraping scenarios.

## 🎯 Purpose

This website is intentionally designed to help developers practice and test:
- Basic HTML scraping
- Navigation handling
- Data extraction from different page structures
- Hero card parsing
- Email extraction
- Header hierarchy analysis

## 📁 Structure

```
├── index.html          # Main page with multiple sections
├── about.html         # Single-section information page
├── contact.html       # Contact information with mailto link
└── heroes.html        # Structured content with hero cards
```

### Page Details

#### index.html
- Main navigation
- Multiple `<h2>` sections
- Narrative paragraphs
- Historical timeline structure

#### heroes.html
- Two main sections (Civilian/Military)
- Card-based layout
- Consistent class naming for heroes
- Nested content structure

#### about.html
- Simple page structure
- Single main content block
- Basic paragraph layout

#### contact.html
- Contact information
- Mailto link
- Simple content structure

## 🔍 Scraping Challenges

1. **Navigation Extraction**
   - All pages contain the same navigation menu
   - Links are relative paths
   - Menu structure is consistent

2. **Hero Data Extraction**
   - Heroes are divided into two categories
   - Each hero has a name and description
   - Consistent class naming (`hero-card`, `hero-name`)
   - Nested information structure

3. **Content Hierarchy**
   - Multiple heading levels
   - Sections with varying depth
   - Consistent class usage

4. **Contact Information**
   - Mailto link extraction
   - Email address parsing
   - Contact form structure (if implemented)

## 📚 Testing Scenarios

Here are some suggested scraping exercises:

1. Extract all hero names and their descriptions
2. Create a navigation map of the site
3. Build a content hierarchy from the index page
4. Extract and validate all internal links
5. Collect all heading text in order
6. Parse hero cards into structured data
7. Extract and validate the contact email

## 🛠️ Technical Details

- Pure HTML/CSS implementation
- No JavaScript dependencies
- Consistent class naming conventions
- Semantic HTML structure
- Mobile-responsive design

## 🔧 Setup for Testing

1. Clone this repository
2. Serve the files using any static web server
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```
3. Access the site at `http://localhost:8000`

## 📝 Notes for Scrapers

- All pages follow a consistent structure
- Class names are semantic and meaningful
- No anti-scraping measures are implemented
- Content is static and doesn't require JavaScript
- All links are relative paths
- Email addresses follow a consistent format

## 🤝 Contributing

Feel free to:
- Add more test scenarios
- Implement new page structures
- Create additional scraping challenges
- Improve documentation

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.