# Volunteering-App
Navigate to Project Directory:

cd volunteer-app/volunteer

Create and Activate Virtual Environment:
Create a virtual environment (Since are using venv):

python -m venv .venv
●	
●	Activate the virtual environment:
On Windows:

.venv\Scripts\activate
○	
On macOS/Linux:

source .venv/bin/activate
○	
Install Dependencies:

pip install -r requirements.txt

●	Make sure requirements.txt includes all necessary dependencies, such as Django and any other libraries used in your project (e.g., Pillow for image handling).
Apply Database Migrations:

python manage.py migrate

Create a Superuser (if needed):

python manage.py create superuser

●	Follow the prompts to set up a superuser account.
Start the Development Server:

python manage.py runserver

●	The development server should start at http://127.0.0.1:8000/.
Access the Admin Interface:
●	Open a web browser and go to http://127.0.0.1:8000/admin/.
●	Log in with the superuser credentials created earlier to access the Django admin interface.
