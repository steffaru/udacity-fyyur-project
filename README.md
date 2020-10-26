🎼🎙🎸🎶🎟 Fyyur 🎼🎙🎸🎶🎟
-----

## Introduction

Fyyur is a musical venue and artist booking site that facilitates the discovery and bookings of shows between local performing artists and venues. This site lets you list new artists and venues, discover them, and list shows with artists as a venue owner.

My job was to build out the data models to power the API endpoints for the Fyyur site by connecting to a PostgreSQL database for storing, querying, and creating information about artists and venues on Fyyur.

## Overview

This app is nearly complete. It is only missing one thing… real data! I'm using a PostgreSQL database.

   ## TO DO'S WHERE DONE 🐱‍💻

* ✅ Creating new venues, artists, and creating new shows.
* ✅ Searching for venues and artists.
* ✅ Learning more about a specific artist or venue.
* ✅ Using SQLAlchemy, set up normalized models for the objects we support in our web app in the Models section of `app.py`
* ✅ Implement missing model properties and relationships using database migrations via Flask-Migrate.
* ✅ Implement form submissions for creating new Venues, Artists, and Shows.
* ✅ Implement the controllers for listing venues, artists, and shows.
* ✅ Implement search, powering the `/search` endpoints that serve the application's search functionalities.
* ✅  Serve venue and artist detail pages, powering the `<venue|artist>/<id>` endpoints that power the detail pages.

We did make that happen!🎉

## Tech Stack (Dependencies) 👩‍💻 

### 1. Backend Dependencies 
Our tech stack will include the following:
 * 💻 **virtualenv** as a tool to create isolated Python environments
 * 🛅 **SQLAlchemy ORM** to be our ORM library of choice
 * 📚 **PostgreSQL** as our database of choice
 * 🐍 **Python3** 
 * 🧪 **Flask** as our server language and server framework
 * 🧰 **Flask-Migrate** for creating and running schema migrations
You can download and install the dependencies mentioned above using `pip` as:

### 2. Frontend Dependencies
You must have the **HTML**, **CSS**, and **Javascript** with [Bootstrap 3].

## Main Files: Project Structure

  ```sh
  ├── README.md
  ├── app.py *** the main driver of the app. Includes your SQLAlchemy models.
      "python app.py" to run after installing dependences
  ├── config.py *** Database URLs, CSRF generation, etc
  ├── error.log
  ├── forms.py *** Your forms
  ├── requirements.txt *** The dependencies we need to install with "pip3 install -r requirements.txt"
  ├── static
  │   ├── css 
  │   ├── font
  │   ├── ico
  │   ├── img
  │   └── js
  └── templates
      ├── errors
      ├── forms
      ├── layouts
      └── pages
  ```


## ROOT OF THIS ACADEMIC PROJECT
⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇⬇

## Development Setup 🔨⛏🔩🧱🧰🔌
1. **Download the project starter code locally**
```
git clone https://github.com/udacity/FSND.git
cd FSND/projects/01_fyyur/starter_code 
```

2. **Create an empty repository in your Github account online.

3. **Initialize and activate a virtualenv using:**
```
python -m virtualenv env
source env/bin/activate
```
>**Note** - In Windows, the `env` does not have a `bin` directory. Therefore, you'd use the analogous command shown below:
```
source env/Scripts/activate
```

4. **Install the dependencies:** 🕳
```
pip install -r requirements.txt
```

5. **Run the development server:** 💨
```
export FLASK_APP=myapp
export FLASK_ENV=development # enables debug mode
python3 app.py
```

6. **Verify on the Browser**<br>🥂💻📱
Navigate to project homepage [http://127.0.0.1:5000/](http://127.0.0.1:5000/) or [http://localhost:5000](http://localhost:5000)  🐱‍🚀

 🖼 Good luck 😊