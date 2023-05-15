# Phonebook App

This is a simple phonebook app built with React and Django.

## Installation

1. Clone the repository: `git clone https://github.com/kemoeverlyne/phonebook-app.git`
2. Install the dependencies for the React app: `cd phonebook-app/frontend && npm install`
3. Install the dependencies for the Django app: `cd ../backend && pip install -r requirements.txt`
4. Create a `.env` file in the server directory and add the required environment variables for your database connection.

## Usage

1. Start the Django server: `cd server && python manage.py runserver`
2. In a separate terminal window, start the React app: `cd frontend && npm start`
3. Open your browser and go to http://localhost:3000 to view the app.

## API Endpoints

### GET /api/contacts

Returns a list of all contacts in the phonebook.

### POST /api/contacts

Adds a new contact to the phonebook.

**Request Body**

```json
{
  "first_name": "John",
  "last_name": "Doe",
  "phone_number": "555-555-5555"
}
```

### GET /api/contacts/:id

Returns a specific contact from the phonebook.

### PUT /api/contacts/:id

Updates a specific contact in the phonebook.

**Request Body**

```json

```

{
"first_name": "John",
"last_name": "Doe",
"phone_number": "555-555-5555"
}

### DELETE /api/contacts/:id

Deletes a specific contact from the phonebook.

### Credits

This app was built by Eva
