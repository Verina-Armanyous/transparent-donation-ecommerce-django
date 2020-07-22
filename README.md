## E-donation platform (ACTONATE) => Pick a cause and Act on it!

The recent data shows that what prevents potential donors from donating is the lack of transparency from the recipient organization's side. We realized, based on our own experiences, because of this, we have to go through a lot of hassle: looking for nonprofits/charities, checking whether they are legitimate, etc. Almost overwhelming and frustrating. Yet, when we do online shopping, it feels fun and easy. We realized it is because we can see what we are giving our money for before we actually pay. Just a couple of clicks, and the purchase is on the way. Therefore, e-commerce inspired us to build this e-donation platform that made donating easy and enabled donors to know what impact their money can create.

## Running this project

To get this project up and running follow these steps:
You can install virtualenv with

```
pip install virtualenv
```

Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project

```
virtualenv env
```

That will create a new folder `env` in your project directory. Next activate it with this command on mac/linux:

```
source env/bin/active
```

Then install the project dependencies with

```
pip install -r requirements.txt
```

Now you can run the project with this command

```
python manage.py runserver
```
