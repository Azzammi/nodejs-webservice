# nodejs-webservice
Membangun Webservice Menggunakan Nodejs

#### Commit Http Verb
- CURL : `curl -X GET http://localhost:5000`

#### Commit Body Request
- CURL : `curl -X POST -H "Content-Type: application/json" http://localhost:5000 -d "{\"name\": \"Dimas\"}"`

#### Commit Routing Request
- `curl -X GET http://localhost:5000`
- `curl -X POST http://localhost:5000`
- `curl -X DELETE http://localhost:5000`
- `curl -X GET http://localhost:5000/about`
- `curl -X POST -H "Content-Type: application/json" http://localhost:5000/about -d "{\"name\": \"Dicoding\"}"`
- `curl -X PUT http://localhost:5000/about`
- `curl -X DELETE http://localhost:5000/about`

#### Commit Response Code
- `curl -X DELETE http://localhost:5000 -i`
- `curl -X GET http://localhost:5000/about -i`
