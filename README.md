# Social Book - A Django-Based Social Media Platform

Social Book is a Django-based social media platform designed to provide users with an engaging social experience. This platform supports user authentication, profile management, post sharing, following other users, liking posts, and searching for profiles. With a focus on simplicity and ease of use, Social Book is a lightweight social media app with core functionalities needed to interact and share content.

![Logo](path_to_your_logo_image)

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Project Structure](#project-structure)
5. [Screenshots](#screenshots)
6. [Contributing](#contributing)
7. [License](#license)

---

## Features

### User Authentication
- **Signup/Login**: Secure user authentication with Django’s built-in authentication system.
- **Logout**: Easily log out from your account.
- **Password Management**: Django's authentication allows for secure password handling.

### Profile Management
- **User Profiles**: Each user has a unique profile with a profile picture, bio, and location.
- **Edit Profile**: Users can update their profile picture, bio, and location.
- **Follow/Unfollow Users**: Users can follow and unfollow each other to create a personalized feed.

### Posts
- **Create Post**: Users can share images with captions to their profile.
- **Like Posts**: Users can like posts shared by others, encouraging engagement.
- **Feed**: View posts from the users you follow in a dynamic feed.
- **Download Posts**: Users can download images from posts.

### Discover & Search
- **Search for Users**: Search functionality to find other users by username.
- **Suggestions**: Discover new users to follow, with personalized suggestions.

### Notifications
- **Follow Notifications**: Get notified when someone follows you (future enhancement).

### Settings
- **Account Settings**: Manage profile settings such as updating profile pictures, bio, and location.

## Installation

To get started with Social Book, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Abhishek3102/Social-Media-Website-using-Django
   cd social-book
   ```

2. **Install Dependencies**:
   Create and activate a virtual environment, then install the required packages:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

3. **Configure the Database**:
   Apply migrations to set up the database.
   ```bash
   python manage.py migrate
   ```

4. **Create a Superuser**:
   Create a superuser to access the Django admin panel.
   ```bash
   python manage.py createsuperuser
   ```

5. **Run the Development Server**:
   Start the server to test the application locally.
   ```bash
   python manage.py runserver
   ```

6. **Access the Application**:
   Open a browser and go to `http://127.0.0.1:8000` to start using Social Book.

## Usage

- **Home Page**: After logging in, users can view their personalized feed.
- **Profile**: Each user has their own profile page where they can see their posts and edit their profile information.
- **Settings**: Modify personal details, profile image, bio, and location.
- **Upload**: Share new posts by uploading images with captions.
- **Search**: Find other users by searching for their username.

## Project Structure

Here's a quick overview of the key directories and files in this project:

- `core/`: Contains the main application logic.
  - `models.py`: Database models for user profiles, posts, and followers.
  - `views.py`: Functions that define the behavior of each view (e.g., profile, settings, upload).
  - `urls.py`: URL routing for core application views.
- `templates/`: Contains HTML templates for the various views (e.g., `index.html`, `signup.html`, `setting.html`).
- `media/`: Directory where uploaded media files, such as profile pictures and post images, are stored.
- `static/`: Contains CSS, JS, and image assets.
- `social_book/`: Project configuration files and global settings.

## Screenshots

Here are some screenshots of Social Book's interface:

1. **Login Page**  
   ![image](https://github.com/user-attachments/assets/43be433f-e11b-4f73-9920-5af6165719a3)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2. **Signup Page**  
   ![image](https://github.com/user-attachments/assets/4febe6b2-8880-400f-8754-db4a9fddd118)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3. **Profile Page**  
   ![image](https://github.com/user-attachments/assets/9e36b7fb-577d-4e5c-8fbb-7f38a4db4bd0)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4. **Settings Page**  
   ![image](https://github.com/user-attachments/assets/120d95e6-206a-40f3-a5ef-3059cadc7ac5)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

5. **Feed Page**  
   ![image](https://github.com/user-attachments/assets/0cdb6363-bc9c-4fc7-80ac-4a96f89c3252)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Contributing

Contributions are welcome! Please fork this repository, make your changes, and open a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to update any section based on the features you plan to enhance or modify in the future. Let me know if you need further help!
