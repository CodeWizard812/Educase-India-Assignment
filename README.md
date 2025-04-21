# Educase-India-Assignment

<h2>Add School API</h2>
<ul>
    <li>Method: POST</li>
    <li>URL: http://localhost:3000/addSchool,</li>
    <li>Headers: Content-Type: application/json</li>
    <li>Body (raw JSON) example:
        {
        "name": "Springfield Public School",
        "address": "Downtown Lane, Pune",
        "latitude": 18.5204,
        "longitude": 73.8567
        }
    </li>
</ul>

<h2>List Schools API</h2>
<ul>
    <li>Method: GET</li>
    <li>URL: http://localhost:3000/listSchools?latitude=18.5089&longitude=73.8037</li>
    <li>Query Parameters:
        {
        latitude: required (e.g., 18.5089)
        longitude: required (e.g., 73.8037)
        }
    </li>
</ul>