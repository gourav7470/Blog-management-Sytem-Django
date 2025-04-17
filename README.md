# Blog Management System

## Introduction
The Blog Management System is a web-based application developed using Django and SQLite. This project automates the existing manual system by providing a robust and efficient computerized solution, ensuring that valuable information can be stored securely and accessed conveniently over an extended period. With this intermediate-level project, you will learn database integration, module usage, and GUI development in Python.

## Project Overview
The Blog Management System has two main modules:
1. **Admin**
2. **Reader (User)**

### Features:
#### Admin Panels:
The admin is the primary user who can control the entire system. Admin has access to:
- **Category Management:** Add, update, or delete categories.
- **Post Management:** Add, update, or delete posts.
- **Tag Management:** Add, update, or delete tags.
- **Change Password:** Update admin password securely.
- **Password Recovery:** Admin can recover their password using appropriate commands.

#### Reader (User) Panel:
- Browse posts by categories and tags.
- Interact with content provided by the admin.

## Technology Stack
- **Backend:** Django Framework
- **Database:** SQLite
- **Frontend:** HTML, CSS, JavaScript
- **Version Control:** Git

## Installation
Follow these steps to set up the Blog Management System:
1. Clone the repository:
    ```bash
    git clone https://github.com/gourav7470/Blog-management-Sytem-Django.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Blog-management-Sytem-Django
    ```
3. Create a virtual environment:
    ```bash
    python -m venv .venv
    ```
4. Activate the virtual environment:
    ```bash
    # For Windows
    .venv\Scripts\activate
    
    # For Mac/Linux
    source .venv/bin/activate
    ```
5. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
6. Run the development server:
    ```bash
    cd blogms
    python manage.py runserver
    ```

## Usage
1. Admin can log in and manage categories, posts, tags, and password settings.
2. Readers can browse posts by categories and tags.

## Future Enhancements
- Add user authentication for Readers.
- Enable comments on blog posts.
- Enhance the GUI for better user experience.

---

Feel free to modify this README to include additional details about your project. Let me know if you need further assistance!
