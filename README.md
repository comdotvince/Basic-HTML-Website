# Basic HTML Website

> **Project**: [Basic HTML Website](https://roadmap.sh/projects/basic-html-website)  
> **Roadmap**: [Frontend Developer Roadmap](https://roadmap.sh/frontend)

A clean, semantic portfolio website built with pure HTML and CSS as part of the roadmap.sh frontend developer learning path. This project demonstrates fundamental web development skills using only vanilla technologies.

## 🎯 Project Requirements Met

✅ **Semantic HTML Structure**: Proper use of HTML5 semantic elements  
✅ **Multiple Pages**: Home, Projects, Articles, Contact pages  
✅ **Navigation**: Consistent navigation across all pages

## 📁 Project Structure

```
Basic-HTML-Website/
├── index.html          # Home page with hero section
├── projects.html       # Projects showcase with grid layout
├── articles.html       # Blog/articles page
├── contact.html        # Contact form and information
└── README.md          # Project documentation
```

## 🌟 Features Implemented

### Core Requirements

- **Semantic HTML5**: `<main>`, `<section>`, `<article>`, `<nav>`, `<header>`, `<footer>`
- **Multi-page Website**: 4 interconnected pages with consistent navigation

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and form validation
- **CSS3**: Flexbox, Grid, responsive design
- **No JavaScript**: Pure HTML/CSS as per requirements
- **No Frameworks**: Vanilla implementation only
- **Claude Sonnet 4**: Documentation and Debugging

## 🎨 Design Approach

### Layout Strategy

- **Semantic Structure**: Proper HTML5 semantic elements
- **Consistent Navigation**: Same header/footer across all pages
- **Clean Typography**: Arial font family for readability

## 📄 Page Breakdown

### Home (index.html)

```html
- Hero section with professional introduction - Two-column content layout -
Projects and Education overview - Clean, professional presentation
```

### Projects (projects.html)

```html
- Responsive grid layout (CSS Grid) - 6 project cards with descriptions -
Auto-fit columns for different screen sizes - Professional project showcase
```

### Articles (articles.html)

```html
- Blog-style article previews - Date stamps and descriptions - Web development
focused topics - Chronological organization
```

### Contact (contact.html)

```html
- Contact form with validation - Name, email, subject, message fields -
Alternative contact methods - Professional contact information
```

## 🚀 Getting Started

### Quick Start

```bash
# Clone the project
git clone [your-repo-url]
cd Basic-HTML-Website

# Open in browser
open index.html
```

## ✅ Learning Outcomes

Through this project, I demonstrated proficiency in:

1. **HTML5 Semantics**: Proper use of semantic elements
2. **CSS Layout**: Flexbox and Grid implementation
3. **Responsive Design**: Mobile-first approach
4. **Form Handling**: HTML5 validation and accessibility
5. **Project Structure**: Multi-page website organization
6. **Web Standards**: Following best practices and accessibility guidelines

## 🔧 Key Implementation Details

### Semantic HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Meta tags and title -->
  </head>
  <body>
    <header><!-- Logo and navigation --></header>
    <main>
      <section><!-- Page content --></section>
    </main>
    <footer><!-- Copyright --></footer>
  </body>
</html>
```

### CSS Layout Approach

```css
/* Flexbox for overall page structure */
body {
  display: flex;
  flex-direction: column;
}

/* Grid for project showcase */
.project-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
}
```

### Form Implementation

```html
<form class="contact-form" action="#" method="POST">
  <input type="text" name="name" required />
  <input type="email" name="email" required />
  <textarea name="message" required></textarea>
  <button type="submit">Send Message</button>
</form>
```

## 🎓 Roadmap.sh Project Completion

This project fulfills all requirements for the [Basic HTML Website](https://roadmap.sh/projects/basic-html-website) project:

- ✅ Created a multi-page website using HTML and CSS
- ✅ Implemented semantic HTML structure
- ✅ Built responsive layouts without frameworks
- ✅ Added functional contact form
- ✅ Maintained consistent navigation and styling
- ✅ Demonstrated fundamental frontend skills

---

_This project is part of my journey through the [roadmap.sh Frontend Developer](https://roadmap.sh/frontend) learning path. It demonstrates foundational HTML and CSS skills essential for modern web development._
