# Book List Manager

A simple, static web application for managing personal reading lists with local storage persistence.

## Overview

Book List Manager is my first static website project, built to understand the fundamentals of web development including HTML structure, CSS styling, and JavaScript DOM manipulation. The application provides a straightforward interface for tracking books you want to read, are currently reading, or have completed.

## Features

- **Add Books**: Input book title, author, and reading status
- **Display Books**: View all books in organized list format
- **Remove Books**: Delete books from your reading list
- **Local Storage**: Persist data between browser sessions
- **Responsive Design**: Works across different screen sizes
- **Simple UI**: Clean, intuitive interface focused on functionality

## Purpose and Learning Objectives

This project was built as a learning exercise to master:

### HTML Fundamentals
- Semantic HTML structure
- Form elements and validation
- List structures and organization
- Proper document structure

### CSS Styling
- Layout techniques
- Styling form elements
- Responsive design basics
- Color schemes and typography

### JavaScript Basics
- DOM manipulation
- Event listeners and handlers
- Local storage API usage
- Array methods and data management
- Function organization and structure

## Technical Implementation

### Tech Stack
- HTML5
- CSS3
- Vanilla JavaScript
- Browser Local Storage API

### Core Functionality

**Data Structure**
```javascript
{
  title: "Book Title",
  author: "Author Name",
  status: "reading" // or "to-read", "completed"
}
```

**Key Features Implementation**
- Form submission handling with JavaScript
- Dynamic DOM creation for book list items
- Local storage for data persistence
- Event delegation for delete functionality
- Form validation and user feedback

## Project Structure

```
Book-List-Manager/
├── index.html          # Main application page
├── styles.css          # Styling
├── script.js           # Application logic
└── README.md          # Documentation
```

## Usage

1. Clone or download the repository
2. Open `index.html` in a web browser
3. Add books using the form
4. Manage your reading list
5. Data persists automatically in browser storage

## Skills Demonstrated

- HTML form creation and handling
- CSS layout and responsive design
- JavaScript DOM manipulation
- Event handling and propagation
- Local storage management
- User input validation
- Clean, readable code structure
- Version control with Git

## Learning Outcomes

Building this project taught me:
- The fundamentals of web development
- How HTML, CSS, and JavaScript work together
- Browser APIs and local storage
- Event-driven programming
- Importance of user experience in simple applications
- Code organization and structure
- Problem-solving in web development context

## Future Enhancements

Potential improvements for learning purposes:
- Add search and filter functionality
- Include book cover images
- Implement categories or genres
- Add reading progress tracking
- Export/import reading lists
- Integration with book APIs for metadata
- Enhanced styling with modern CSS techniques
- Accessibility improvements

## Limitations

As a first project, this application has intentional simplicity:
- Single-user, local-only storage
- No backend or database integration
- Basic styling and UI
- Limited features compared to production applications

These limitations were appropriate for a first project focused on learning core web development concepts.

## Author

**Ruben Sauer Cloete**

Full-Stack Developer | EdTech Specialist

- LinkedIn: [Ruben Sauer Cloete](https://linkedin.com/in/rubensauer-cloete-359207389)
- GitHub: [many-miles](https://github.com/many-miles)
- Email: rscloete10@gmail.com

## Acknowledgments

This project represents my first step into web development, providing the foundation for more complex applications like SkillGet and SG-Directory.

---

**First Static Web Project | Learning Exercise | 2024**
