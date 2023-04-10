# Image Uploader
trying to implement the things I learned in Django 
The Code is present in the master branch 

This project is a simple image uploader web application built with Django. Users can upload images to the application, and the uploaded images will be displayed on the home page. The uploaded images can be viewed individually, and users can also delete the uploaded images.

## Installation

1. Clone the repository:

git clone https://github.com/Quinos2003/ImageUploader.git

2. Change into the project directory:

cd imageuploader

3. Create a virtual environment:

python3 -m venv env

4. Activate the virtual environment:
bash

source env/bin/activate

5. Install the dependencies:

pip install -r requirements.txt

6. Create the database:

python manage.py migrate

7. Create a superuser:

python manage.py createsuperuser

8. Run the development server:

python manage.py runserver

9. Access the application at http://localhost:8000.
Usage
Register or log in to the application.
Click on the "Upload" button to upload an image.
Click on the image to view it.
Click on the "Delete" button to delete the image.
Contributing
Contributions are welcome! Please open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
