Installation: Go to your desired folder.

Run the command: git clone https://github.com/amitkumariitmadras/ghanshyam-interview.git

Go to the directory with requirements.txt.

Run the command: python -m venv venv

After a venv directory is created,
run the command for windows: venv\Scripts\activate.bat
run the command for Unix or MacOS: source venv/bin/activate

Ensure latest version of pip by running: python -m pip install --upgrade pip

Install the dependencies by running the command: pip install -r requirements.txt

We need multiple devices in the same LAN for testing. For that we need to make our localhost public.
For that, download ngrok from https://ngrok.com/download and install it.

Usage:
From the directory where we have installed venv, go to the mysite directory by running the command: cd mysite

To start the development server, run the command: python manage.py runserver