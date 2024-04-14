# Feedback_system
# Feedback Form with Django

This is a simple feedback form project built using Django, where users can submit feedback along with ratings.

## Getting Started

Follow these instructions to download, set up, and run the project locally on your machine.

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- Python (https://www.python.org/)
- Django (https://www.djangoproject.com/)

### Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/feedback-form.git

2. Navigate to the project directory:
 ```bash
   cd feedback-form

3. Create a virtual environment (optional but recommended):
      python -m venv venv

4. Activate the virtual environment On Windows:
      venv\Scripts\activate

5. Setting Up the Database (Apply database migrations):
     python manage.py migrate

6.Create a superuser account:
      python manage.py createsuperuser
  Follow the prompts to enter a username, email, and password for the superuser.

7. Running the Project
  1. Start the Django development server:
        python manage.py runserver

  2. Open your web browser and go to http://127.0.0.1:8000/ to access the project.

  3. Log in to the admin panel using the superuser credentials created earlier at http://127.0.0.1:8000/admin/.
