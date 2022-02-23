# Educative-Viewer

## This project was made for easier readability of courses of Educative.io HTML files scraped using [Educative.io_Scraper](https://github.com/anilabhadatta/educative.io_scraper)

## To run this project:

### Step 1: Create a virtual environment using:

#### > (For Windows) python -m venv env

#### > (For MacOS) python3 -m venv env

### Step 2: Activate the environment

#### > (For Windows) env\Scripts\activate

#### > (For MacOS) source env/bin/activate

### Step 3: Install the dependencies using:

#### > (For Windows) pip install -r requirements.txt

#### > (For MacOS) pip3 install -r requirements.txt

### Step 4: Run the following command in the virtual environment:

#### > (For Windows) python educative-scraper.py

#### > (For MacOS) python3 educative-scraper.py

### Step 5: Enter the course folder path in terminal and server will automatically start
#### > Enter localhost:5000 in your desktop browser to open the viewer
#### > Enter local_server_address:5000 in your mobile browser to open the viewer
#### > Refer the image below to get the course folder path, eg: "/Users/anilabhadatta/Documents/temp-course"
![image](https://i.imgur.com/sQQlJGI.jpg)

### Step 6 (Optional): To build the python application using pyinstaller:

#### Install pyinstaller in your system virtual environment using pip

#### > (For Windows) pyinstaller --clean --add-data templates;templates --onefile -i"icon.ico" educative-viewer.py

#### > (For MacOS) pyinstaller --clean --add-data templates:templates --onefile -i"icon.ico" educative-viewer.py
