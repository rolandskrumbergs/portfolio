# Overview

This is a personal portfolio website for Rolands Krumbergs, a .NET Developer & Architect. The website showcases professional experience, technical skills organized by expertise level, certifications, and languages in a clean, minimalist design. It's built as a single-page application using vanilla HTML, CSS, and JavaScript with a focus on clean design and smooth user interactions.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Single-page application** built with vanilla HTML, CSS, and JavaScript
- **Component-based structure** with separate files for different concerns:
  - `index.html` - Main structure and content
  - `styles.css` - CSS with custom properties for theming and responsive design
  - `script.js` - Main application logic and navigation
- **CSS-first approach** using custom properties for consistent theming and maintainable styles
- **Responsive design** with mobile-first methodology

## Data Storage
- **No backend required** - fully static website 
- **No persistent data storage** needed
- **Contact information** displayed statically (email, LinkedIn, location)

## Navigation & UX
- **Smooth scrolling** between sections
- **Mobile-responsive navigation** with hamburger menu
- **Intersection Observer** for scroll animations and active navigation states
- **Static contact information** display with direct email/LinkedIn links
- **Feather Icons** integration for consistent iconography

# External Dependencies

## Third-party Libraries
- **Feather Icons** (v4.29.0) - Icon library loaded from CDN for consistent, lightweight icons throughout the interface

## Browser APIs
- **Intersection Observer API** - For scroll-triggered animations and navigation highlighting

## No Backend Dependencies
- Fully static website with no server-side components
- No database connections required
- No authentication system needed
- All functionality runs entirely in the browser