# Technology-Today-Assignment
A full-stack social media site built with PHP, MySQL, and Bootstrap 5. Features user authentication, article reactions via AJAX, a commenting system, and dynamic profile pages.  Developed as an assignment for the Computer Science and Software Engineering course at the University of Abertay, Dundee "Web Development" 2025.

### Live demo: [https://mayar.abertay.ac.uk/~2407591/index.php]

## Tech Stack
Backend: PHP 8, MySQL (PDO)
Frontend: Bootstrap 5, vanilla JavaScript (AJAX)
Auth: Session-based with bcrypt password hashing
Compliance: WCAG AA, UK GDPR / Data Protection Act 2018

## Features
User registration and login with bcrypt-hashed passwords
Session-based authentication with session_regenerate_id() on login
Two-tier user roles (Level 1: post & comment / Level 2: post, comment & delete)
Article feed with Bootstrap hero carousel on the home page
Like / dislike reactions via AJAX - no page reload
Comment system stored in MySQL and rendered via PHP includes
User profile pages dynamically generated from URL user ID
User search bar accessible to all visitors
SQL injection protection via PDO prepared statements throughout
Cascade deletes — removing a user also removes all their posts, comments, and reactions
Responsive layout across desktop and mobile, tested on Chrome and Firefox
