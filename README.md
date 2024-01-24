# Ecommerce Web Application

Welcome to the GitHub repo of "Sunny's Sunshine Corner", the e-store where you can browse and order beautiful embroidery designs, designed and hand-made by Ms Sunnyeong Ahn.
The application was designed following Dennis Ivy online course

The web app was built in the Django framework, while HTML, CSS/Bootstrap and Javascript were used for the front-end. For now, I use Javascript to reload the *whole* page whenever there is an update, but I am currently redesigning the app to use HTTP requests and jQuery for the sake of efficiency.


## To run locally
The site is still under construction so I haven't yet deployed it. However, we can run it locally by following the following steps:

1. Fork this repo, and cd to the project directory
```
cd ecommerce
```

2. Create and activate a Python virtual environment, then install the required packages and libraries:
```
pip install -r requirements.txt
```

3. Start the development server. 
```
py manage.py runserver
```

4. By default, the server runs on the internal IP (127.0.0.1) on port 8000. To interact with the web app, go to url http://127.0.0.1:8000/.
