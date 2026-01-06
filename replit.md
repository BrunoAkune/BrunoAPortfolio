# Bruno Akune Portfolio

## Overview

This is a personal portfolio website for Bruno Akune, a Business Analyst student showcasing research projects, data analysis work, and technical skills. The application is built with Flask and serves multiple HTML pages highlighting different aspects of the portfolio including qualitative research, quantitative analysis, database projects, data visualization dashboards, and an about page. The site includes integrations with weather and BMI calculation APIs to demonstrate API integration capabilities.

## Recent Changes (December 10, 2025)

**Basketball API Project Integration**:
- **basketball.html**: NBA Statistics Dashboard project page
  - Los Angeles Lakers game statistics dashboard using BallDontLie API
  - Complete Problem/Role/Impact structure highlighting full-stack development
  - Skills section: Python, FastAPI, Plotly & Dash, API Integration
  - Flask route /basketball added to main.py
  - "View Live Dashboard" button links to GitHub Pages hosted demo
- **index.html**: Added "Basketball API" and "Study Analysis" buttons to header navigation
- **Basketball-API/basket-ball.py**: Source code for the dashboard
  - Live demo hosted on GitHub Pages: https://brunoakune.github.io/Basketball-API/
  - Dashboard preview screenshot added to basketball.html

**Crime Analysis Consolidation & R Project Page Creation**:
- **Python.html**: Now renamed as "Crime Analysis Projects" page, consolidating all crime-related projects:
  - ML Crime Forecast (Python machine learning model for Toronto crime prediction)
  - Tableau Crime Statistics Dashboard (commercial building safety analysis)
  - GIS Convenience Store Robbery Map (spatial crime analysis)
  - Each project includes complete Problem/Role/Impact sections
  - Updated navigation bar with smooth-scroll links to all three crime projects
- **R-Project.html**: NEW page created for R programming projects
  - Contains R Case Study (statistical analysis of academic performance)
  - Complete Problem/Role/Impact structure, Skills section, and Contact Me
  - New Flask route /r-project added to main.py
- **dashboard.html**: Updated after moving crime projects
  - Now contains: Power BI Dashboard, Customer Churn Tableau Dashboard, Tobacco Infographic, GIS Projects (Blue Jays Nesting + Influenza Outbreak maps only)
  - Crime Statistics and Convenience Store Robbery moved to Python.html
  - GIS section description and role updated to reflect ecological and public health focus only

**Previous Changes (November 24, 2025)**:
- Applied Problem → Role → Impact structure across all project pages
- **Retail_database.html**: Reorganized with Problem/Role/Impact structure
- **Design Pattern**: All pages maintain alternating wrapper/wrapper style2 CSS classes for consistent visual rhythm

## User Preferences

Preferred communication style: Simple, everyday language.
Contact Information: bruno.akune@gmail.com, LinkedIn: linkedin.com/in/brunoakune

## System Architecture

### Frontend Architecture

**Technology Stack**: Static HTML5
- Pure HTML, CSS, and JavaScript
- Hosted as a Static Deployment on Replit
- Responsive design supporting multiple breakpoints (xlarge, large, medium, small, xsmall, xxsmall)
- Client-side interactivity powered by jQuery for smooth scrolling and animations

**Structure**:
- All HTML pages stored in the root or `public` directory
- Static assets (CSS, JavaScript, images) organized in `static` directory
- Pages include: index.html, CER.html, Python.html, Retail_database.html, dashboard.html, about-me.html, basketball.html, R-Project.html, RCaseStudy.html

### Backend Architecture

**Current Implementation**: None (Static Site)
- Removed Flask backend to enable free Static Deployment
- No server-side processing or API routing

**RATIONALE**: Switched to a static architecture to leverage Replit's free static hosting while maintaining all portfolio content.

### Data Storage

**Current Implementation**: No persistent database
- Portfolio content is hardcoded in HTML templates

## External Dependencies

### Third-Party APIs

**Note**: Weather and BMI API integrations were removed during the transition to a static site to enable free hosting.

### External Libraries and Frameworks

**Python Dependencies** (via requests library):
- `requests`: HTTP library for API calls
- `Flask`: Web framework for routing and template rendering

**Frontend Libraries**:
- jQuery 3.6.0: DOM manipulation and event handling
- Font Awesome 5.15.4: Icon library for UI elements
- Custom JavaScript utilities: breakpoints.js, browser.js, scrolly.js for responsive behavior and smooth scrolling

**Analytics**:
- Google Tag Manager (GTM-TQP4CPXC): Integrated for tracking user interactions and page views

### Static Assets and Templates

**HTML5 UP Fractal Template**
- Purpose: Provides professional, responsive design foundation
- License: CCA 3.0 (free for personal and commercial use)
- Components: Pre-built CSS, JavaScript, and layout structures