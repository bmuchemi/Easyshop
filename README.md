![](https://www.ashwinhariharan.tech/blog/thinking-of-building-a-contact-tracing-application-heres-what-you-can-do-instead/index.png)

# Easyshop

> Community driven delivery platform for the ones who need it the most

### App Screenshot

![](https://miro.medium.com/max/1835/1*ROFwy3bSYmWy39qLmlTZTw.png)

## Instructions to install

1.  **Install PostgreSQL and PostGIS**
    I highly recommend a Docker installation: - Install [Docker](https://docs.docker.com/get-docker/) - Download and run the official [PosgreSQL/PostGIS docker image](https://registry.hub.docker.com/r/postgis/postgis/)

        Alternatively, you can perform an installation directly on the host operating system:
        - [Download](https://www.postgresql.org/download/) the official PostgreSQL installer for your system.
        - [Install](https://postgis.net/install/) the PostGIS extension

2.  **Install `python` and `pip3`**

3.  **Install [GDAL](https://gdal.org/) (Required for Django to interface with PostGIS)**

    - `sudo apt-get install libpq-dev python-dev`
    - `sudo apt-get install binutils libproj-dev gdal-bin`

4.  **Create a python virtual environment using `venv`**
    `python -m venv venv`

5.  **Activate virtual environment**
    `./venv/Scripts/activate`

6.  **Install Django and other dependencies**
    `pip install -r requirements.text`

## Instructions to run

**Start Django web server (Make sure the virtual environment is activated)**
`python manage.py runserver`

# Have any questions?

Say _hi_ 👋 on:

- [Whatsapp](wa.me/+254774811916)
- [Email](mailto:your.bmuchemi55@gmail.com)
