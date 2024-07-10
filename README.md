# 🎉 Feedback Collection System 🎉

Welcome to the Feedback Collection System! This Django-based application allows users to submit their name and feedback, which is stored in a SQLite3 database and can be viewed through the Django admin panel. The project leverages Django's ModelForms to handle form creation and validation efficiently.

## 🌟 Features

- 📝 User-friendly form for submitting name and feedback.
- ✔️ Form validation to ensure data integrity.
- 💾 Feedback stored in a SQLite3 database.
- 🔑 Admin panel for viewing and managing feedback entries.

## 🚀 Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### 🛠️ Prerequisites

- 🐍 Python 3.x
- 🌐 Django 3.x
- 📦 SQLite3 (included with Django)

### 📥 Installation


1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/feedback-collection-system.git
   cd feedback-collection-system
   
2.**Create and activate a virtual environment:**
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3.**Install the dependencies:**
pip install -r requirements.txt

4.**Apply the migrations:**
python manage.py migrate

5.**Create a superuser to access the admin panel:**
python manage.py createsuperuser

6.**Run the development server:**
python manage.py runserver

7.**Open your browser and navigate to:**
http://127.0.0.1:8000/

8.**Here you can fill out the feedback form and submit it. To view the feedback entries, go to the admin panel at:**
http://127.0.0.1:8000/admin

### 🗂️ Project Structure
1.feedback/ - Main application directory

2.feedback/forms.py - Form definitions using Django ModelForms

3.feedback/models.py - Database models for storing feedback

4.feedback/views.py - View functions for handling requests

5.feedback/templates/ - HTML templates for rendering forms and responses

6.project_name/settings.py - Project settings

7.project_name/urls.py - URL routing

### 📝 Usage

Submit Feedback:

Enter your name and feedback in the form on the homepage and click "Submit".

If the form is valid, your feedback will be saved, and you'll see a thank you message. If not, you'll be prompted to correct any errors.

**View Feedback:**
Log in to the admin panel using the superuser account you created.

Navigate to the feedback entries and manage them as needed.

### 🤝 Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.


**Happy coding! 🎉**

   
