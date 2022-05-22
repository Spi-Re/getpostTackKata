# getpostTackKata

![kata-postgettask](https://user-images.githubusercontent.com/96742357/169684185-4ccfdc63-cafe-4c65-bc93-a2c7a11ae65c.png)


JSON 
{"info":{"_postman_id":"1b48b206-4da0-43a6-8499-23357a90328b","name":"kata-task","schema":"https://schema.getpostman.com/json/collection/v2.0.0/collection.json"},"item":[{"name":"Registration","id":"42cf4a57-082d-4871-8d4b-abf6b577ba98","request":{"method":"POST","header":[{"key":"","value":"","type":"text"}],"body":{"mode":"raw","raw":"{\r\n  \"user\": {\r\n    \"username\": \"SpiRe\",\r\n    \"email\": \"vanya.burmistrov007@gmail.com\",\r\n    \"password\": \"1234567890\"\r\n  }\r\n}","options":{"raw":{"language":"json"}}},"url":{"raw":"https://kata.academy:8021/api/users","protocol":"https","host":["kata","academy"],"port":"8021","path":["api","users"],"query":[{"key":"users","value":null,"disabled":true}]}},"response":[]},{"name":"Authentication","id":"b413c6ca-fe45-4795-b011-f949a73165a9","request":{"method":"POST","header":[],"body":{"mode":"raw","raw":"{\r\n  \"user\": {\r\n    \"email\": \"vanya.burmistrov007@gmail.com\",\r\n    \"password\": \"1234567890\"\r\n  }\r\n}","options":{"raw":{"language":"json"}}},"url":"https://kata.academy:8021/api/users/login"},"response":[]},{"name":"Get Current User","id":"b6e9c05e-5e29-45d6-9b49-0299dcaaff0f","request":{"method":"GET","header":[{"key":"Authorization","value":"Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYyODllMTBmZmQyMTFjMjEwMGRiMzkwZSIsInVzZXJuYW1lIjoic3BpcmUiLCJleHAiOjE2NTgzODc2MjMsImlhdCI6MTY1MzIwMzYyM30.sm_M2loAn6Hvog5H2nP82dzGdSpE_gnb0W52MyjRCq8","type":"text"}],"url":"https://kata.academy:8021/api/user"},"response":[]}],"auth":{"type":"bearer","bearer":{}},"event":[{"listen":"prerequest","script":{"id":"3651144e-e0ca-4405-bd52-40d93fae2ea0","type":"text/javascript","exec":[""]}},{"listen":"test","script":{"id":"13b7ac9f-d7ef-4f34-b745-1be1b7f6cc8a","type":"text/javascript","exec":[""]}}]}


Responce после get user-a
{
    "user": {
        "username": "spire",
        "email": "vanya.burmistrov007@gmail.com",
        "token":      "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYyODllMTBmZmQyMTFjMjEwMGRiMzkwZSIsInVzZXJuYW1lIjoic3BpcmUiLCJleHAiOjE2NTgzODg5MDEsImlhdCI6MTY1MzIwNDkwMX0.eVhIYfaNhaBruV_  L6COoaCuWhkpBcar8DJeojVtO9lk"
    }
}
