Gallery
Gallery is a django application that allows users display their photos for others to see.
Requirements
Clone the the repository by running
git clone https://github.com/farzana583/Best-Gallery
or download a zip file of the project from github then unzip.
Navigate to your project directory
Create a virtual environment
Install Virtualenv
pip install virtual venv
To create a virtual environment named virtual, run
virtualenv virtual
To activate the virtual environment we just created, run
source virtual/bin/activate
Create a database
You'll need to create a new postgress database, Type the following command to access postgress
$ psql
Then run the following query to create a new database named picsgarage
create database gallery
Install dependencies
To install the requirements from requirements.txt file,
pip install -r requirements.txt
Create Database migrations
Making migrations on postgres using django run
python3 manage.py makemigrations garage
then run the command below;
python3 manage.py migrate
## Run the app
To run the application on your development machine,
python3 manage.py runserver
## Running Tests
To run tests
python3 manage.py test
## Technologies Used
- Django
- Python
- Html
- Css
- Javascript
- Bootstrap
## User stories
As a user of the application I should be able to:
View different photos that interest me.
Click on a single photo and also view the details of the photo. The photo details must appear on a modal within the same route as the main page.
Search for different categories of photos. (e.g food, nature,sports,places)
Copy a link to the photo to share with my friends.
View photos based on the location they were taken.

MIT License
Copyright (c) [2020] [Farzana Isack]
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated docum entation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
Copyright (c) {2021} **{Farzana Isack}**