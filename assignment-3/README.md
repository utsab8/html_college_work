# LAB ASSIGNMENT 3: HTML & CSS Fundamentals – Static Web Page Design

## Assignment Title
**Designing a Static Management System Web Interface Using HTML and CSS**

## Objective
The objective of this lab assignment is to help students apply basic HTML and CSS concepts to design a structured and visually clear static web interface for a management-oriented application. Students will practice semantic markup, layout using normal document flow, spacing, and basic styling techniques.

## Brief Description
This project implements a **Student Management System** - a static web interface designed to manage student information, academic records, and administrative tasks for educational institutions. The system provides a centralized platform with multiple interconnected pages that demonstrate proper use of HTML5 semantic elements and CSS3 styling techniques.

The interface includes a home page with system introduction, a login page for user authentication, a dashboard with system statistics, and a data listing page displaying student information in a structured table format. All pages are linked through a consistent navigation menu, and the design follows normal document flow using block and inline-block elements without advanced CSS features.

## Technologies Used
- **HTML5** - Semantic markup and structure
- **CSS3** - Basic styling only (no Flexbox, Grid, Position, or Media Queries)

## Constraints Followed
✅ No Flexbox  
✅ No CSS Grid  
✅ No Position property (relative, absolute, fixed, sticky)  
✅ No Media queries  
✅ Layout achieved using block and inline-block elements  
✅ Normal document flow maintained  

## List of Pages

### 1. Home Page (`index.html`)
- **Purpose:** Introduction and overview of the Student Management System
- **Features:**
  - Header with application title and college name
  - Navigation menu using unordered list
  - Introduction section describing the system
  - Key features list
  - System overview section
  - Getting started instructions
  - Footer with copyright information

### 2. Login Page (`login.html`)
- **Purpose:** User authentication interface
- **Features:**
  - Centered login form using margin and width
  - Username and password input fields with labels
  - Submit button
  - Simple, clean layout
  - Consistent navigation menu

### 3. Dashboard Page (`dashboard.html`)
- **Purpose:** System overview and statistics
- **Features:**
  - Page heading with welcome message
  - Summary boxes displaying key statistics:
    - Total Students
    - Active Courses
    - Faculty Members
    - Departments
  - Summary boxes aligned using inline-block elements
  - Recent activities list
  - Quick actions section

### 4. Data Listing Page (`list.html`)
- **Purpose:** Display student information in tabular format
- **Features:**
  - Comprehensive table with student data
  - Table headers (thead) for column names
  - Multiple rows of student information
  - Alternating row colors using CSS nth-child selector
  - Hover effects on table rows
  - Proper table structure with caption

## HTML Elements Used

- **Headings:** h1, h2, h3, h4, h5, h6
- **Paragraphs:** p
- **Lists:** ul, ol, li
- **Tables:** table, thead, tbody, tr, th, td, caption
- **Forms:** form, input, label, button
- **Semantic tags:** header, nav, section, article, footer
- **Anchor tags:** a (for navigation)
- **Images:** img (placeholder for future use)

## CSS Concepts Applied

- **External CSS file** - All styles in separate `css/style.css` file
- **Color properties** - Text and background colors
- **Font styling** - font-family, font-size, font-weight
- **Borders** - Various border styles and colors
- **Padding and margin** - Spacing control
- **Width and height** - Element sizing
- **Box model** - Understanding content, padding, border, margin
- **Hover effects** - Interactive elements
- **Class and ID selectors** - Targeted styling
- **Block and inline-block elements** - Layout control
- **Normal document flow** - Natural element positioning

## Folder Structure
```
assignment-3/
│
├── index.html          # Home Page
├── login.html          # Login Page
├── dashboard.html      # Dashboard Page
├── list.html           # Student List Page
│
├── css/
│   └── style.css       # External CSS file
│
├── images/             # Images folder (for future use)
│
└── README.md           # This documentation file
```

## Steps to Run the Project

### Prerequisites
- A modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari)
- No additional software or server required

### Running Instructions

1. **Navigate to Project Directory**
   - Open the `assignment-3` folder on your computer

2. **Open the Home Page**
   - **Method 1:** Double-click `index.html` to open in your default browser
   - **Method 2:** Right-click `index.html` → "Open with" → Choose your browser
   - **Method 3:** Drag and drop `index.html` into an open browser window
   - **Method 4:** In browser, press `Ctrl + O` (or `Cmd + O` on Mac) and select `index.html`

3. **Navigate Between Pages**
   - Use the navigation menu at the top of each page
   - Click on "Home", "Login", "Dashboard", or "Student List" links
   - All pages are interconnected through anchor tags

4. **View Different Pages**
   - **Home Page:** View system introduction and features
   - **Login Page:** See the centered login form
   - **Dashboard:** View summary boxes and statistics
   - **Student List:** Browse the table with alternating row colors

## Screenshots Required

Please take screenshots of the following pages for submission:

1. **Home Page Screenshot**
   - Shows the complete home page with header, navigation, introduction sections, and footer
   - File: `screenshot-home.png` or `screenshot-home.jpg`

2. **Login Page Screenshot**
   - Shows the centered login form with username and password fields
   - File: `screenshot-login.png` or `screenshot-login.jpg`

3. **Dashboard Page Screenshot**
   - Shows the dashboard with summary boxes displaying statistics
   - File: `screenshot-dashboard.png` or `screenshot-dashboard.jpg`

4. **Student List Page Screenshot**
   - Shows the table with student data and alternating row colors
   - File: `screenshot-list.png` or `screenshot-list.jpg`

5. **Folder Structure Screenshot**
   - Shows the project folder structure with all files and directories
   - File: `screenshot-folder-structure.png` or `screenshot-folder-structure.jpg`

## Design Features

### Navigation
- Consistent navigation menu on all pages
- Hover effects on navigation links
- Easy access to all sections

### Layout
- Centered main content area
- Proper spacing using margin and padding
- Summary boxes aligned using inline-block
- Responsive width using percentage and max-width

### Styling
- Professional color scheme (blues and grays)
- Clear typography hierarchy
- Consistent borders and shadows
- Hover effects for interactivity
- Alternating table row colors for readability

### Forms
- Clean, centered login form
- Proper label-input associations
- Focus states for better UX
- Styled submit button with hover effect

## Code Organization

- **Separation of Concerns:** HTML structure completely separated from CSS styling
- **Semantic HTML:** Proper use of semantic elements (header, nav, section, footer)
- **External CSS:** All styles in external CSS file (no inline or internal CSS)
- **Consistent Naming:** Clear and descriptive class and ID names
- **Clean Code:** Well-formatted and organized code structure
- **Comments:** Minimal comments for clarity

## Browser Compatibility

Tested and compatible with:
- Google Chrome (latest version)
- Mozilla Firefox (latest version)
- Microsoft Edge (latest version)
- Safari (latest version)

## Student Information

- **Name:** Utsab Acharya
- **Student ID:** 2410412031
- **College:** Patan College for Professional Studies
- **Program:** Bachelor of Science in Computer Science

## Evaluation Criteria Coverage

- ✅ **HTML structure and semantics (25%)** - Proper semantic elements used throughout
- ✅ **CSS styling and layout (25%)** - Comprehensive styling with all required concepts
- ✅ **Proper navigation between pages (15%)** - All pages linked with anchor tags
- ✅ **Folder structure and organization (15%)** - Correct folder structure maintained
- ✅ **README and documentation (20%)** - Complete documentation with all required information

## Academic Integrity

This work is submitted as original academic work. All code has been written following the assignment requirements and constraints. The project demonstrates understanding of HTML5 semantic elements and CSS3 basic styling techniques without using advanced features.

## Notes

- This is a static web interface with no backend functionality
- Forms are for display purposes only (no form processing)
- All navigation is handled through HTML anchor tags
- The design follows normal document flow without advanced CSS positioning
- Layout is achieved using block and inline-block elements
- All styling is contained in the external CSS file

## Date
January 2026

## Author
Utsab Acharya - Student Management System Project

