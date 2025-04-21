# Educase-India-Assignment

<h2>Add School API</h2>
Method: POST
URL: http://localhost:3000/addSchool
Headers: Content-Type: application/json
Body (raw JSON) example:
{
  "name": "Springfield Public School",
  "address": "Downtown Lane, Pune",
  "latitude": 18.5204,
  "longitude": 73.8567
}

<h2>List Schools API</h2>
Method: GET
URL: http://localhost:3000/listSchools?latitude=18.5089&longitude=73.8037
Query Parameters:
{
latitude: required (e.g., 18.5089)
longitude: required (e.g., 73.8037)
}