# Real Estate Website

This is a Django-based web application for a real estate company. It allows users to browse available properties, filter by various criteria, and contact the company to schedule a viewing.

The application was built by following a tutorial from the JustDjango YouTube channel.

## Features

- Property listings with photos, descriptions, and various details (e.g. number of bedrooms, bathrooms, square footage)
- Filtering by price range, number of bedrooms, and other criteria
- Contact form for users to send inquiries to the real estate company
- Admin interface for managing property listings, inquiries, and other data

## Setup

To run this application on your local machine, you will need to have Python 3.x, Django, and a few other dependencies installed. Here are the basic steps to get started:
1. Clone this repository to your local machine.
2. Create a virtual environment and activate it.
3. Install the required packages by running `pip install -r requirements.txt`.
4. Apply the database migrations by running `python manage.py migrate`.
5. Load some initial data (optional) by running `python manage.py loaddata fixtures/initial_data.json`.
6. Start the development server by running `python manage.py runserver`.
7. Open your web browser and navigate to http://localhost:8000 to see the application in action.

## Credits

This project was created by [Your Name Here] by following a tutorial from the JustDjango YouTube channel.

Some of the code and design elements are based on the tutorial, but modifications were made to adapt the project to our own needs.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
