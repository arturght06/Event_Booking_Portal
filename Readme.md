# EVE.NT

Portal for booking and managing cultural events, featuring both a web application and a native Android mobile app.

This project was developed for the "UAIM" course at the Warsaw University of Technology (WEITI, PW).

## Authors
* Artur Sliepchenko
* Karol Adamski
* Bartłomiej Masiak
* Denys Moldovan

## Features
* **Multi-Platform Access:** Fully functional React-based Web Application and a native Java Android App.
* **Event Management:** Users can browse, create, edit, delete, and book places for events.
* **Social Interactions:** Built-in commenting system for event pages.
* **Notifications & Reminders:** Global notification system and automated email reminders for upcoming events.
* **Advanced Filtering:** Filter events by categories and sort them to find exactly what you need.
* **User Dashboard:** Dedicated profiles for managing created events, reservations, custom locations, and categories.
* **Secure & Scalable Architecture:**
  * Backend REST API built with Flask.
  * Secure JWT-based authentication.
  * Fully containerized environment using Docker and Docker Compose.
  * Automated deployment scripts for VPS hosting.

## Tech Stack
* **Web Client:** React, Vite, React Router DOM, CSS Modules
* **Mobile Client:** Java, Android SDK, Navigation Component
* **Backend API:** Python, Flask, SQLAlchemy, Flask-Mail, JWT
* **Database:** PostgreSQL
* **Infrastructure & Deployment:** Docker, Docker Compose, Bash scripts, Cloudflare Tunnels
