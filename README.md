<!-- HEADER: BEGIN -->
<div align="center">

<img src="asset\images\Educore_logo.png" alt="EduCore" height="120" />

# EduCore  
**School Website Content Management System**

![Status](https://img.shields.io/badge/status-active-success)
![Platform](https://img.shields.io/badge/platform-government-blue)
![PHP](https://img.shields.io/badge/PHP-7.x+-8892BF)
![Framework](https://img.shields.io/badge/Framework-CodeIgniter-red)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen)
![Last Commit](https://img.shields.io/github/last-commit/HVzz24/EduCore)


EduCore is developed using PHP with the CodeIgniter framework and follows a modular MVC architecture. The system supports PHP versions 5.6 to 7.4, making it suitable for deployment on both legacy and modern server environments.

The frontend is designed with a responsive layout to ensure usability across desktop and mobile devices. The backend provides an administrative interface for website configuration, content management, and news publishing.

---
</div>
<!-- HEADER: END -->


## Features

### Content Management

- **News & Articles:** Create, edit, and publish news articles and blog posts.
- **Static Pages:** Easily manage static content pages like 'About Us', 'Contact', or 'Terms of Service'.
- **Photo Albums:** Organize and display images in photo albums.
- **Video Playlists:** Create and manage video playlists.
- **Event Agenda:** Announce and manage upcoming events and schedules.
- **File Downloads:** Provide downloadable files for your users.
- **Alumni Directory:** Maintain a directory of alumni members.
- **Content Organization:**
    - **Categories:** Group your content into different categories.
    - **Tags:** Use tags to further classify your content.

### Engagement & Interaction

- **User Polling:** Create and manage polls to gather user opinions.
- **Contact Form:** A built-in contact form for user inquiries.
- **Consultation Requests:** Allow users to submit consultation requests.

### Administration

- **Administrator Panel:** A comprehensive admin panel to manage all aspects of the website.
- **User Management:** Manage users and their roles/permissions.

## Showcase

Here are some visual overview of the project:

-   **Homepage Demo:**   [View demo video](asset/images/Homepage.mp4)

-   **Admin Panel Dashboard:**
  [View demo video](asset/images/adminpage.mp4)
        
    
## Technical Stack

- **Backend:** PHP
- **Framework:** CodeIgniter 3
- **Database:** MySQL
- **Web Server:** Apache with `mod_rewrite` enabled

## Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/EduCore.git
    ```

2.  **Environment:**
    - Set up a LAMP (Linux, Apache, MySQL, PHP) or XAMPP server.
    - Ensure Apache's `mod_rewrite` module is enabled.

3.  **Database:**
    - Create a new MySQL database named `educore`.
    - **Note:** A database schema file (`educore.sql`)

4.  **Configuration:**
    - **Database:** Open `application/config/database.php` and set your database connection details (hostname, username, password).
    - **Application:** Open `application/config/config.php` and set the following:
        - `base_url`: Your project's root URL (e.g., `http://localhost/EduCore/`).
        - `encryption_key`: A strong, random string for session encryption.

## Running the Application

- Access the application by navigating to your configured `base_url`.
- The administrator panel is located at `base_url/administrator`.

### Admin Credentials

- To log in to the admin panel, you will need to create a user in the database or use 
```
Username : Admin
Password : admin
```
- The password must be hashed using `sha512(md5($password))`.

---
