<!-- HEADER: BEGIN -->
<div align="center">

<img src="asset\images\Educore_logo.png" alt="EduCore" height="120" />

# EduCore  
**Government Website Content Management System**

![Status](https://img.shields.io/badge/status-active-success)
![Platform](https://img.shields.io/badge/platform-government-blue)
![PHP](https://img.shields.io/badge/PHP-7.x+-8892BF)
![Framework](https://img.shields.io/badge/Framework-CodeIgniter-red)
![License]()
![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen)
![Last Commit](https://img.shields.io/github/last-commit/HVzz24/EduCore)


EduCore is a Content Management System (CMS) built with CodeIgniter 3, designed for educational or news-oriented websites. It provides a simple and effective way to manage your website's content.

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

Here are some suggestions for what you can showcase with screenshots to give a visual overview of the project:

-   **Homepage:**
    -   **Description:** The main landing page of your website, giving the first impression to your visitors. It should highlight the latest news, events, and other important information.
    -   **Screenshot:** `[Your Homepage Screenshot]`

-   **News/Article Page:**
    -   **Description:** A view of a single news article, showing the title, content, author, and date.
    -   **Screenshot:** `[Your Article Page Screenshot]`

-   **Photo Album/Gallery:**
    -   **Description:** The gallery page, displaying a collection of photos in an album.
    -   **Screenshot:** `[Your Gallery Screenshot]`

-   **Events/Agenda Page:**
    -   **Description:** A list of upcoming events, with dates and brief descriptions.
    -   **Screenshot:** `[Your Events Page Screenshot]`

-   **Admin Panel Dashboard:**
    -   **Description:** The main dashboard of the administrator panel, showing statistics and quick links to different management sections.
        - **Screenshot:** `[Your Admin Dashboard Screenshot]`
    
    -   **Admin - Add New Article:**
        -   **Description:** The form used to create or edit a news article in the admin panel, showcasing the rich text editor and other fields.
        -   **Screenshot:** `[Your Add Article Screenshot]`
    
    
    
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
    - **Note:** A database schema file (`.sql` dump) is not included in the project. You will need to manually create the database tables based on the application's models and controllers.

4.  **Configuration:**
    - **Database:** Open `application/config/database.php` and set your database connection details (hostname, username, password).
    - **Application:** Open `application/config/config.php` and set the following:
        - `base_url`: Your project's root URL (e.g., `http://localhost/EduCore/`).
        - `encryption_key`: A strong, random string for session encryption.

## Running the Application

- Access the application by navigating to your configured `base_url`.
- The administrator panel is located at `/administrator`.

### Admin Credentials

- To log in to the admin panel, you will need to create a user in the database.
- The password must be hashed using `sha512(md5($password))`.

---
