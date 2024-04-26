# email-java-api

api -  curl -X POST "http://localhost:8080/api/email-key?email=(почта на которую отправить письмо с кодом)"


ответ от api -  json {"status":(true(отправлено) - false(не отправлено),"authenticationKey":"key"}

пример: {"status":true,"authenticationKey":"TPbwz3"}