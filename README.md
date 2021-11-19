# youtube_fetch_api
An API to fetch latest videos from youtube sorted in reverse chronological order of their publishing date-time from YouTube for a given tag/search query in a paginated response.
The server fetches latest videos async after every 10 minutes and saves it to the database.
This project is completely based on Django.

Technologies Used

Used Cron Jobs django_cron to fetch videos after every 10 minutes using Youtube Data Api and save it to the database.

Setup Guide

->Clone the project

->As this project is based on Django, your system need to have proper python setup.

-> Go the project through the terminal and install all dependencies by using typing pip install -r requirements.txt in the terminal.

-> Inside the setting.py file, fill the variable GOOGLE_API_KEYS with all the API Keys available,the list should be filled as ['API_KEY_1','API_KEY_2',...].

->Run the server using python mange.py runserver
