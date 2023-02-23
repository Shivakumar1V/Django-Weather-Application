
#  Django Weather Application

This weather application is built using Django, requests and openweathermap, here users can get weather information by entering the city name
## Requirements
`api_key` is required to run this project, to get `api_key` follow the below steps
* Create an account in **[openweathermap.org](https://openweathermap.org/)**
* After creating account **[click here](https://home.openweathermap.org/api_keys)** to go to openweathermap api_keys section here you can generate a new `api_key` or stick with default `api_key`
## Run Locally

Clone the project

```bash
  git clone https://github.com/Shivakumar1V/Django-Weather-Application
```

Install dependencies

```bash
  pip install -r requirements.txt
```

* Now open `views.py` file which is in `home/views.py` and enter your **openweathermap** `api_key` in `api_key = "your api_key"` section and save the file

Run the below commands
```bash 
  python manage.py makemigrations
  python manage.py migrate
```

Start the server

```bash
  python manage.py runserver
```

It will run the application on [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

**Yeah!** Now the application is ready to use  
Open your browser and go to **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)** and enjoy the application