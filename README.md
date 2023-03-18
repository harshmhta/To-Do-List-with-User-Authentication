# Django To-Do List Web Application with User Authentication

This is a Django To-Do list web application with user authentication, search functionality, and full CRUD (Create, Read, Update, and Delete) operations. Users can register and log in to their account to create, manage and delete their own to-do list items.

## Features

1. User registration and login

2. Create, read, update, and delete to-do list items

3. Search functionality to find specific to-do list items

4. Responsive design for mobile and desktop

5. Django 3.2 and Python 3.9.7 used in development

## Screenshots

#### Login Page:

<img width="1440" alt="Screen Shot 2023-03-17 at 5 45 03 PM" src="https://user-images.githubusercontent.com/58926340/226074359-3e2769b4-91e2-4ba8-9088-bc2b33dbe70a.png">

#### Home Page:

<img width="1440" alt="Screen Shot 2023-03-17 at 5 46 01 PM" src="https://user-images.githubusercontent.com/58926340/226074367-cc35f551-c77e-4006-89ef-d98f1cbbc29a.png">

#### Add Task Page:

<img width="1440" alt="Screen Shot 2023-03-17 at 5 52 26 PM" src="https://user-images.githubusercontent.com/58926340/226074447-c1f749b3-ca5e-41ad-b04f-6ee616e6d9cc.png">

## Installation

#### Clone the repository:
```
git clone https://github.com/<your-github-username>/django-todo-list-app.git
```
#### Change into the directory:
```
cd django-todo-list-app
```
#### Install the dependencies:
```
pip install -r requirements.txt
```
#### Create the database tables:
```
python manage.py migrate
```
#### Run the server:
```
python manage.py runserver
```
Open your web browser and navigate to ```http://localhost:8000/```

#### To create account with admin access, use command:

```
python manage.py createsuperuser
```

Then navigate to ```http://localhost:8000/admin``` and login using credentials

## Usage

1. Register a new account by clicking on the "Register" link on the page.

2. Log in to your account.

3. Create a new to-do list item by clicking on the "New Task" button and filling out the form.

4. View all of your to-do list items on the home page.

5. Edit or delete a to-do list item by clicking on the corresponding buttons.

6. Search for a specific to-do list item by entering a keyword in the search bar on the page.

7. Log out of your account by clicking on the "Logout" button on the page.

## Contributing

Contributions are welcome! If you find any bugs or have any suggestions for new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
