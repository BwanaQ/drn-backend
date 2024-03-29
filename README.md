# DJANGO REACT NATIVE BACKEND

A Djangorestframework based RESTful backend to be served with a React Native Frontend.

## Getting Started

- clone this repo

```
$ git clone https://github.com/BwanaQ/drn-backend.git
```

### Prerequisites

- Python 3 latest version
- Pip3 installer
- virtualenv command

### Installing

1. cd into the fast_food folder

```
$ cd fast_food
```

2. Add a python 3 environment

```
$ virtualenv env
```

3. Enter the virtual environment

```
$ source env/bin/activate
```

4. Install dependancies from requirements.txt

```
(env)$ pip install -r requirements.txt
```

5. rename .env copy to .env, add all those fields with your correct values, save it then run this command

```
(env) $ source .env
```

6. Run server

```
(env) $ python manage.py runserver
```

## Deployment

to deploy to heroku simply create a project and attach your git hub repository

## Built With

- [Django](https://www.djangoproject.com/) - The web framework used
- [Django Rest framework](https://www.django-rest-framework.org/) - For the API Endpoints.

## Authors

- **Tom Hunja**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- Thanks to [Toptal](https://www.toptal.com/developers/gitignore/api/django) for a beautiful .gitignore file
