# Strava auto kudos bot

a Selenium Python bot that gives kudos to the newest posts on the "following" page of Strava.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You'll need

```
python3
selenium
decouple
```

### Installing

A step by step series of examples that tell you how to get a development env running

#### Install python with needed packages

Install python 3 from [python.org](https://www.python.org/)

Next, install selenium, so that our script can do browser automation

```
pip install selenium
```

And decouple, so that we can read sensitive data (that for obvious I haven't uploaded to the internet) from a `.env` file

```
pip install python-decouple
```

#### Env variables

To login to strava make a `.env` file in which you'll store your email and password.

**.env**

```
EMAIL=youremail@emaildomain.com
PASSWORD=yourpassword
```

## Authors

- **Vlatko Stojkoski** - _Initial work_ - [VlatkoStojkoski](https://github.com/VlatkoStojkoski)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details