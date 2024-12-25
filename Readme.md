# server setup instructions
git clone https://github.com/khurshid/test.git

npm i

npm start

# api use instructions
## register api
host: http://localhost:3000/register

method: POST

payload: 
`
{
    "username":"admin",
    "password":"password"
}`
## login api
host: http://localhost:3000/login

method: POST

payload:
`{
    "username":"admin",
    "password":"password"
}`
## jwt verify
host: http://localhost:3000/verify-jwt

method: GET

Authorization Bearer token: <receievd from login>
