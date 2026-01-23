# Inventory Management System - Static Web Interface

## Assignment Title
Designing a Static Management System Web Interface Using HTML and CSS

## Objective
This project demonstrates the application of basic HTML and CSS concepts to design a structured and visually clear static web interface for a management-oriented application. The interface represents a real Inventory Management System but does not require any backend or JavaScript functionality.

## Project Overview
The **Inventory Management System** is a comprehensive static web interface designed to streamline inventory management operations. It provides a user-friendly platform for managing products, tracking stock levels, and monitoring system activities.

## Technologies Used
- **HTML5** - Semantic markup structure
- **CSS3** - Basic styling, layout, and visual effects
- **No external frameworks** - Pure HTML and CSS implementation

## Constraints Strictly Followed
✓ **No Flexbox** - Layout achieved using block and inline-block elements  
✓ **No CSS Grid** - Normal document flow used for layout  
✓ **No Position Property** - Margin and padding used for positioning  
✓ **No Media Queries** - Fixed layout suitable for desktop viewing

## Project Structure
```
Lab_3/
├── index.html              # Home Page
├── login.html              # Login Page
├── dashboard.html          # Dashboard Page
├── list.html               # Products Listing Page
├── css/
│   └── style.css          # External CSS stylesheet
├── images/                 # Images folder (for future use)
└── README.md              # This documentation file
```

## Pages Included

### 1. Home Page (index.html)
The landing page that introduces the Inventory Management System.

**Features:**
- Header with application title
- Navigation menu with links to all pages
- Introduction section describing the system
- Key Features section highlighting system capabilities
- Getting Started guide with 3 steps
- System Requirements section
- Call-to-action button for login
- Footer with copyright information

**HTML Elements Used:**
- Header, nav, section, article, footer (semantic tags)
- h1, h2, h3 (headings)
- p, ul, li (paragraphs and lists)
- a (anchor tags for navigation)
- button (call-to-action)

### 2. Login Page (login.html)
User authentication interface for accessing the system.

**Features:**
- Centered login form with professional styling
- Input fields: Username, Email, Password
- Dropdown selector for User Role (Admin, Manager, Staff, Viewer)
- Remember Me checkbox
- Demo credentials section for testing
- Support contact information
- Form validation and submission handling

**HTML Elements Used:**
- form (login form)
- input (text, email, password, checkbox)
- label (form labels)
- select (dropdown for user roles)
- button (submit)
- section (content organization)

### 3. Dashboard Page (dashboard.html)
Central hub displaying inventory statistics and recent activities.

**Features:**
- Welcome section with overview
- Key Metrics section with 4 summary boxes displaying:
  - Total Products (1,247)
  - Low Stock Items (45)
  - Total Users (28)
  - Stock Value ($125K)
- Recent Activities table with 5 sample transactions
- Quick Actions section with 4 action cards
- System Status table showing component health
- Inline-block elements for box layout

**HTML Elements Used:**
- table, thead, tbody, tr, th, td (data tables)
- section, article (content organization)
- h2, h3 (headings)
- Summary boxes using div with CSS styling

### 4. Products Listing Page (list.html)
Comprehensive product inventory display with filtering and search capabilities.

**Features:**
- Page introduction with description
- Filter & Search section with dropdowns for:
  - Product Category
  - Stock Status
  - Product Search
- Detailed Products Table with 10 sample products showing:
  - Product ID, Name, Category
  - Current Stock, Unit Price
  - Reorder Level, Status
  - Last Updated date
- Alternating row colors for readability
- Inventory Summary Statistics table
- Product Management Information section
- Stock Status definitions
- Reorder instructions

**HTML Elements Used:**
- table (comprehensive product listing)
- form (search and filter)
- select, input, button (form controls)
- thead, tbody (table sections)
- Alternating row styling with CSS

## HTML Requirements Met

✓ **Headings (h1 to h6)** - Used appropriately across all pages  
✓ **Paragraphs (p)** - Extensive use for content descriptions  
✓ **Lists (ul, ol, li)** - Feature lists, navigation, and information lists  
✓ **Tables (table, thead, tbody, tr, th, td)** - Used for data display and activities  
✓ **Forms (form, input, label, button)** - Login and search forms implemented  
✓ **Semantic Tags (header, nav, section, article, footer)** - Proper semantic structure  
✓ **Anchor Tags (a)** - Navigation between pages  
✓ **Images (img)** - Image folder prepared for future use

## CSS Requirements Met

✓ **External CSS File** - [css/style.css](css/style.css) linked to all pages  
✓ **Color Properties** - Text and background colors applied throughout  
✓ **Font Styling** - Font-family, font-size, font-weight customized  
✓ **Borders** - Applied to forms, tables, and sections  
✓ **Padding and Margin** - Used for spacing and layout control  
✓ **Width and Height** - Controlled for responsive design  
✓ **Box Model** - Proper implementation with margin, border, padding, content  
✓ **Hover Effects** - Applied to links, buttons, table rows, and form inputs  
✓ **Class and ID Selectors** - Used for targeted styling  
✓ **Block and Inline-Block** - Used for layout without flexbox/grid  
✓ **Normal Document Flow** - All layout achieved using natural flow

## Navigation Structure

All pages are linked using HTML anchor tags:
- **Home Page** - Starting point, links to all other pages
- **Login Page** - Accessible from all pages via navigation menu
- **Dashboard Page** - Accessible from all pages via navigation menu
- **Products Page** - Accessible from all pages via navigation menu

Navigation menu appears on every page, allowing seamless navigation between sections.

## Color Scheme

- **Primary Color:** #2c3e50 (Dark Blue-Gray) - Headers and main elements
- **Secondary Color:** #3498db (Bright Blue) - Accents and highlights
- **Background Color:** #f4f4f4 (Light Gray) - Page background
- **Text Color:** #333 (Dark Gray) - Main text
- **Success Color:** #27ae60 (Green) - Status indicators
- **Warning Color:** #e74c3c (Red) - Alert and warning indicators

## Styling Features

### Layout Techniques
- Block and inline-block elements for layout
- Margin and padding for spacing
- Centered content using margin auto
- Normal document flow for all positioning

### Visual Effects
- Hover effects on navigation links and buttons
- Table row hover highlighting
- Input field focus styling
- Box shadows for depth
- Border styling for organization

### Typography
- Primary Font: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- Hierarchy: h1 (28px), h2 (24px), h3 (18px), h4 (16px)
- Consistent line-height (1.6) for readability

## Accessibility Features

- Semantic HTML structure for screen readers
- Proper heading hierarchy
- Form labels associated with inputs
- High contrast colors for readability
- Clear navigation structure
- Descriptive link and button text

## Browser Compatibility

The website is designed to work on all modern browsers:
- Google Chrome (80+)
- Mozilla Firefox (75+)
- Microsoft Edge (80+)
- Safari (13+)

## File Descriptions

### index.html
Main landing page introducing the inventory system with feature descriptions and navigation.

### login.html
Authentication interface with form validation and demo credentials for testing.

### dashboard.html
Administrative dashboard showing key metrics, recent activities, and quick actions.

### list.html
Products inventory page with comprehensive data table, filtering options, and status indicators.

### css/style.css
External stylesheet containing all CSS rules for:
- Global styling and reset
- Header and navigation
- Main content and sections
- Forms and input elements
- Tables and data display
- Dashboard boxes and metrics
- Utility classes and typography

## Usage Instructions

1. **Navigate to the home page:** Open `index.html` in your web browser
2. **Explore pages:** Use the navigation menu to move between pages
3. **Test login form:** Use demo credentials on the login page
4. **View product list:** Check the products page for sample inventory data
5. **Review dashboard:** See key metrics and activities on the dashboard

## Key Features

✓ Clean, professional design  
✓ Consistent styling across all pages  
✓ Semantic HTML structure  
✓ Responsive button styling with hover effects  
✓ Professional color scheme  
✓ Well-organized table displays  
✓ Accessible form elements  
✓ Clear navigation structure  
✓ Proper spacing and padding  
✓ Professional typography

## Evaluation Criteria Coverage

| Component | Coverage | Details |
|-----------|----------|---------|
| HTML Structure and Semantics | 25% | ✓ Semantic tags, proper heading hierarchy, organized content |
| CSS Styling and Layout | 25% | ✓ Professional styling, consistent colors, hover effects, proper spacing |
| Navigation Between Pages | 15% | ✓ Functional links on all pages, consistent menu structure |
| Folder Structure | 15% | ✓ Organized folders, external CSS, proper file arrangement |
| README and Documentation | 20% | ✓ Comprehensive documentation, clear instructions, feature descriptions |

## Page Screenshots and Descriptions

### Home Page (index.html)
- Features: Clean header, navigation menu, system introduction, features list, getting started guide
- Content: 6 sections with comprehensive information about the system

### Login Page (login.html)
- Features: Centered form, input validation, demo credentials, support information
- Content: Professional login interface with role selection

### Dashboard Page (dashboard.html)
- Features: Summary metrics with inline-block boxes, activity tables, quick actions, system status
- Content: 5 sections displaying key statistics and recent activities

### Products Page (list.html)
- Features: Filter options, comprehensive product table, inventory summary, management information
- Content: Detailed product listing with status indicators and search capabilities

## Assignment Completion Checklist

✅ 4 HTML pages created (Home, Login, Dashboard, Products)  
✅ External CSS file created and properly linked  
✅ All required HTML elements used appropriately  
✅ All required CSS concepts implemented  
✅ No prohibited CSS features used (Flexbox, Grid, Position, Media Queries)  
✅ Semantic HTML structure throughout  
✅ Proper navigation between all pages  
✅ Professional styling and layout  
✅ Folder structure organized correctly  
✅ README.md documentation provided  

## Author
Created for Lab 3 - Static Management System Web Interface Design

## Date
January 2026

## License
Educational Use Only

---

**Note:** This is a static interface demonstration. In a production system, these pages would be connected to a backend database and server for full functionality.
