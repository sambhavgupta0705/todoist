Hey Everyone!!

Todoist is a simple TODO application built using Django, allowing users to create, manage, and mark tasks as completed.
## Features
- User Authentication: Users can sign up, log in, and manage their tasks securely.
- Task Management: Create, edit, delete tasks and mark them as completed.
- Responsive Design: The application is designed to be responsive and accessible on various devices.
- User-specific Tasks: Each user has their own set of tasks, maintaining privacy.


## Requirements
- Python 3.7
- Django 3.2
- Additional requirements specified in requirements.txt


## Installation 
1. Clone the respository
``` git clone https://github.com/yourusername/todoist.git```
2. Navigate to the project directory:
```cd todoist```
3. Create a virtual environment:
```python3 -m venv env```
4. Activate the virtual environment:
- On Windows:
```env\Scripts\activate ```
- On macOS and Linux:
```source env/bin/activate```
5. Install Dependencies
```pip install -r requirements.txt```
6. Run database migtations
```python manage.py migrate```
7. Start the development server:
```python manage.py runserver```
8. Access the application at http://127.0.0.1:8000/ in your web browser.

## Usage
1. Create a new account or log in with existing credentials.
2. Once logged in, you can:
- Add a new task.
- View existing tasks.
- Edit or delete tasks.
- Mark tasks as completed.
3. Log out to securely exit your account.


## Contribution
Contributions are welcome! If you'd like to improve this application, feel free to fork the repository and submit a pull request with your changes.


## License
This project is licensed under the [MIT License](https://opensource.org/license/mit/).
