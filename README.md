# Job_Portal

A web-based Job Portal developed using Django that connects job seekers and employers on a single platform. The application allows employers to post job vacancies and candidates to search and apply for jobs efficiently.

## Features

### For Job Seekers

* User Registration and Login
* Profile Management
* Browse Available Jobs
* Search Jobs by Title, Location, and Skills
* Apply for Jobs
* View Applied Jobs

### For Employers

* Employer Registration and Login
* Create and Manage Company Profile
* Post New Job Openings
* Edit and Delete Job Listings
* View Applicants for Posted Jobs

### Admin Features

* Manage Users
* Manage Job Listings
* Monitor Applications
* System Administration through Django Admin Panel

## Technologies Used

* Python
* Django
* HTML5
* CSS3
* Bootstrap
* JavaScript
* SQLite (Development)
* MySQL (Optional)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Bhumi2708/Job_Portal.git
```

2. Navigate to the project directory:

```bash
cd Job_Portal
```

3. Create a virtual environment:

```bash
python -m venv venv
```

4. Activate the virtual environment:

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

5. Install dependencies:

```bash
pip install -r requirements.txt
```

6. Apply migrations:

```bash
python manage.py migrate
```

7. Run the development server:

```bash
python manage.py runserver
```

8. Open your browser and visit:

```text
http://127.0.0.1:8000/
```

## Project Structure

```text
Job_Portal/
│
├── manage.py
├── requirements.txt
├── db.sqlite3
├── templates/
├── static/
├── media/
└── apps/
```

## Future Enhancements

* Resume Upload and Parsing
* Email Notifications
* Job Recommendations using AI
* Interview Scheduling
* Skill Assessment Tests
* Real-Time Chat between Recruiters and Candidates

## Author

Bhumika Sham Gujar

## License

This project is developed for educational and learning purposes.
