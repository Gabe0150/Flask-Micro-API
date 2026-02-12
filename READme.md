FIU Campuses API

A lightweight Flask REST API that provides GET and POST functionality for managing FIU campus location data. The API returns JSON responses and allows users to retrieve campus information or add new campus entries.

Features

Health check endpoint

Retrieve all campuses

Retrieve a single campus by ID

Add a new campus via POST request

Endpoints
Health Check
GET /api/health

Get All Campuses
GET /api/items

Get Campus by ID
GET /api/items/<id>

Add New Campus
POST /api/items


Example JSON body:

{
  "campus": "Tamiami",
  "lat": 25.75,
  "lon": -80.40
}

Installation

Clone the repository

Install dependencies:

pip install -r requirements.txt


Run the app:

python app.py


The server will run at:

http://127.0.0.1:5000
