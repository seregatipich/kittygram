# kittygram

Kittygram is an application that allows you to browse and download cat photos.

## Installation

To run this script on your computer, follow these steps:

1. Clone the repository using the command
```
git clone git@github.com:seregatipich/kittygram.git
``` 

2. Navigate to the application directory using the command
```
cd kittygram
``` 

3. Create virtual environment
```
python -m venv venv
```

4. Activate virtual environment
```
source venv/Scripts/activate
```
or
```
source venv/bin/activate
```

5. Install the dependencies from requirements.txt
```
pip install -r requirements.txt
```

Make migrations:
```
python manage.py migrate
```

## Usage

1. Run the site
```
python3 manage.py runserver
```
2. After launching, you will be able to access it using any browser on you computer via this link: 
```
127.0.0.1:8000  
```

## License

This project is licensed under the MIT License. You are free to use it in your projects.
