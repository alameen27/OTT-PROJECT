# OTT Platform Web Application

This project is a web application designed to deliver an Over-The-Top (OTT) platform for on-demand video streaming. Inspired by services like Amazon Prime Video and Netflix, the platform includes modules for managing content, creators, and users. Built with Django and MySQL, it provides a robust and scalable solution for video streaming.

## Features

### Core Modules
- **Content Management**: Add, edit, and manage video content, including categories and metadata.
- **Content Creator Management**: Manage content creator profiles and contributions.
- **User Management**: Handle user registration, authentication, subscription plans, and profiles.

### Frontend
- Designed with HTML, CSS, and Bootstrap for a responsive and user-friendly interface.
- Utilizes Django Templates for seamless integration with backend logic.

### Backend
- Built with Django's MVT (Model-View-Template) architecture.
- Utilizes Django ORM for efficient database operations and queries.

### Database
- MySQL database with Django ORM for data storage, management, and relationships.
- Features optimized queries and a normalized schema for scalability.

## Technology Stack

- **Frontend**:
  - HTML
  - CSS
  - Bootstrap
  - Django Templates

- **Backend**:
  - Django (MVT architecture)
  - Django ORM for database interactions

- **Database**:
  - MySQL

## Installation and Setup

### Prerequisites
- Python (v3.8 or higher)
- MySQL Server
- pip (Python package installer)

### Steps

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd ott-platform
   ```

2. **Backend Setup**:
   - Navigate to the backend folder:
     ```bash
     cd backend
     ```
   - Install Python dependencies:
     ```bash
     pip install -r requirements.txt
     ```
   - Set up the database:
     - Create a MySQL database named `ott_platform`.
     - Update the `settings.py` file with your database credentials.
     - Apply migrations:
       ```bash
       python manage.py makemigrations
       python manage.py migrate
       ```
   - Run the Django development server:
     ```bash
     python manage.py runserver
     ```

3. **Frontend Setup**:
   - No additional setup is required for the frontend, as Django Templates handle integration.

4. **Access the Application**:
   - Open your browser and navigate to `http://localhost:8000`.

## Usage

1. **User Registration and Login**:
   - Users can register, log in, and manage their profiles.

2. **Content Management**:
   - Admin users can add, update, or delete video content.

3. **Content Creator Management**:
   - Manage creator details and associate them with content.

4. **Video Streaming**:
   - Users can browse, search, and stream videos on demand.

## Contribution

If you wish to contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any inquiries or feedback, please contact:
- **Email**: [Your Email Address]
- **LinkedIn**: [Your LinkedIn Profile]
